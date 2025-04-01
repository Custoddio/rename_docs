🚀 Renomeador de Arquivos 🚀

Este script em Python foi feito para facilitar a renomeação de arquivos em uma pasta específica. Ele vai reduzir o nome dos arquivos para no máximo 50 caracteres (sem mexer nas extensões, claro 😅), e te mantém informado com alertas pop-up durante o processo. 💥

📝 Funcionalidade ✨
Percorre todos os arquivos de uma pasta específica (definida pela variável folder).

Renomeia os arquivos, limitando seus nomes a no máximo 50 caracteres (preservando a extensão). Super simples! 😎

Durante o processo, o script exibe alertas usando pyautogui.alert():

Um alerta antes de renomear, avisando que o nome será encurtado. 📝

Um alerta depois, confirmando que o arquivo foi renomeado com sucesso. ✔️

📦 Dependências 📦
Para rodar esse script, você vai precisar do Python 3.x e da biblioteca pyautogui. Não se preocupe, vou te guiar! 😊

Para instalar a dependência, basta rodar:

bash
Copiar
pip install pyautogui
⚙️ Como usar ⚙️
Clone ou baixe o repositório no seu computador. 💻

Altere o caminho da pasta na variável folder para o local dos arquivos a serem renomeados. Exemplo:

python
Copiar
folder = r"C:\Users\SeuUsuario\Documents\SuaPasta"
Execute o script e ele começará a renomear os arquivos. Você verá alertas aparecendo, para ficar por dentro de tudo! 😄

🖥️ Exemplo de uso 🖥️
Para rodar o script, basta usar o comando:

bash
Copiar
python renomear_arquivos.py
Após a execução, todos os arquivos da pasta terão seus nomes truncados para no máximo 50 caracteres, e você verá alertas confirmando o sucesso de cada renomeação. 🎉

⚠️ Avisos Importantes ⚠️
Atenção! Certifique-se de que o script tem permissão para modificar os arquivos da pasta. 👀

Lembre-se: A execução do script não é reversível. Os nomes dos arquivos serão alterados permanentemente. Então, faça backup antes de rodar, se necessário! 💾
