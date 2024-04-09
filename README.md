# Name

epc-qr-code - Generate a EPC QR Code

# Synopsis

    epc-qr-code "John Smith" "DE12345678901234567890" "123.45" "Test" 

# Description

epc-qr-code is a posix shell script that generates a QR code for a
SEPA Credit Transfer. It takes the name of the recipient, the IBAN,
the amount in Euro and a text as arguments. The BIC can be passed as
an option. The script uses its only dependency qrencode to
generate the QR code.

The options are as follows:

- --bic=BIC

    The BIC of the recipient's bank.

# See also

qrencode(1), [https://en.wikipedia.org/wiki/EPC_QR_code](https://en.wikipedia.org/wiki/EPC_QR_code)

# License

MIT
