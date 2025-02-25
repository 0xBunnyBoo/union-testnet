
Original file line number	Diff line number	Diff line change
@@ -5,7 +5,7 @@
  "network_type": "testnet",
  "pretty_name": "Union Testnet",
  "chain_type": "cosmos",
  "chain_id": "union-testnet-8",
  "chain_id": "union-testnet-9",
  "bech32_prefix": "union",
  "daemon_name": "uniond",
  "node_home": "$HOME/.uniond",
@@ -32,36 +32,18 @@
    ]
  },
  "peers": {
    "seeds": [
      {
        "id": "c2bf0d5b2ad3a1df0f4e9cc32debffa239c0af90",
        "address": "testnet.seed.poisonphang.com:26656",
        "provider": "poisonphang"
      }
    ]
    "seeds": [ ]
  },
  "apis": {
    "rpc": [
      {
        "address": "https://rpc.testnet-8.union.build",
        "address": "https://rpc.testnet-9.union.build",
        "provider": "union"
      },
      {
        "address": "https://union-testnet-rpc.polkachu.com",
        "provider": "Polkachu"
      },
      {
        "address": "https://rpc-testnet-union.nodeist.net",
        "provider": "Nodeist"
      },
      {
        "address": "https://union-testnet-rpc.itrocket.net",
        "provider": "ITRocket"
      }
    ],
    "rest": [
      {
        "address": "https://rest.testnet-8.union.build",
        "address": "https://rest.testnet-9.union.build",
        "provider": "union"
      },
      {
@@ -79,20 +61,8 @@
    ],
    "grpc": [
      {
        "address": "grpc.testnet-8.union.build",
        "address": "grpc.testnet-9.union.build",
