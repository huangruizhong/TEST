# TEST
'''python
from websocket import create_connection
ws = create_connection("wss://openapi.digifinex.com/ws/v1/")
ws.send('{"id":12312, "method":"server.ping", "params":[]}')
print(ws.recv())

'''
