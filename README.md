# helpful_scripts

Just some scripts that I find useful

## decode_url_base64 
This script will need libmagic and python-magic installed 

this script takes urls and a parameter in it and will base64 decode it and if it is a type that is recognisable to be compressed it will do that. 

the output is the hex for what is decoded, the string value if possible, the mime type and the encoding used to decode the string 

we try decoding with utf8 first then , latin1, utf-16, utf-32 and finally ascii 

meh
