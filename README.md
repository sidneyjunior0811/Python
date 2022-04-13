# Python

Para instalar o 'pytesseract' no Windows, segue o passo a passo abaixo:


01 - Clicar no link: https://github.com/UB-Mannheim/tesseract/wiki 

Depois clique em um dos dois que seja a configuração do seu computador:

tesseract-ocr-w32-setup-v5.0.1.20220118.exe (32 bit)
tesseract-ocr-w64-setup-v5.0.1.20220118.exe (64 bit)

02 - Você irá clicar em 'Next' até aparecer a janela com o endereço onde o arquivo será instalado, e então copie o endereço e cole no bloco de notas;

03 - Depois instale o Pacote 'pip install pytesseract';

04 - Após a instalação, você irá copiar e colar no seu CODE o seguinte código

(pytesseract.pytesseract.tesseract_cmd = r'C:\Users\USER\AppData\Local\Tesseract-OCR\tesseract.exe)
