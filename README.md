# qrcode_Python #

# instalar #

# pip install PyQRCode #

# pip install pypng #

import pyqrcode
import png
from pyqrcode import QRCode

#Link desejado para o QRCode 
QRString = 'http://www.google.com'

#Monta o QRCode 
url = pyqrcode.create(QRString)

#Salva o QRCode gerado no local desejado 
url.png(r'imagem.png', scale=8)

