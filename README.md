# Trabalho-Estrutura-de-Dados

 PRÉ-REQUISITOS
1. Instalar Compilador C (GCC)
Windows: Opção A - MinGW (Recomendado): 1. Baixe MinGW:
https://www.mingw-w64.org/downloads/
2. Instale seguindo o assistente
3.Adicione ao PATH: C:\mingw64\bin

Opção B - Dev-C++: 
1. Baixe: https://www.bloodshed.net/devcpp.html
2.Instale normalmente
3. Já vem com GCC integrado

Linux (Ubuntu/Debian):
sudo apt update
sudo apt install gcc
macOS:
xcode-select --install

 PREPARAR ARQUIVOS
1. Criar pasta para o projeto:
C:\SAPA\
2. Copiar estes arquivos para a pasta:
• sapa_final_corrigido.c
• datatran2021.csv (dataset)

 EXECUTAR O PROGRAMA
MÉTODO 1: Prompt de Comando (Windows)

1. Abrir CMD:
• Pressione Windows + R
• Digite cmd
• Pressione Enter

3. Navegar para a pasta:
cd C:\SAPA

4. Compilar:
gcc -o sapa.exe sapa_final_corrigido.c -lm

5. Executar:
sapa.exe

MÉTODO 2: PowerShell (Windows)
1. Abrir PowerShell:
• Pressione Windows + X
• Escolha “Windows PowerShell”
2. Navegar:
cd C:\SAPA
3. Compilar e executar:
gcc -o sapa.exe sapa_final_corrigido.c -lm
.\sapa.exe
MÉTODO 3: Terminal (Linux/Mac)
1. Abrir terminal
2. Navegar:
cd /caminho/para/pasta/SAPA
3. Compilar:
gcc -o sapa sapa_final_corrigido.c -lm
4. Executar:
./sapa

 SOLUÇÃO DE PROBLEMAS
Erro: “gcc não é reconhecido”
Solução: GCC não está instalado ou não está no PATH - Reinstale MinGW -
Adicione C:\mingw64\bin ao PATH do Windows
Erro: “arquivo não encontrado”
Solução: Arquivo CSV não está na pasta - Copie datatran2021.csv para a
mesma pasta do programa
Erro: “permission denied”
Solução: Sem permissão de execução - Linux/Mac: chmod +x sapa
Programa não responde
Solução: Aguardando entrada - Digite um número (0-8) e pressione Ente
