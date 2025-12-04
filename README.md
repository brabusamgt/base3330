# base3330
Python Snippet: Tracking Deposits/Withdrawals to Base Bridge
bridge = "0x...bridgeAddress"
logs = w3.eth.get_logs({"address": bridge})
print(logs)
