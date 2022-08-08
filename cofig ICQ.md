# I used the below config.yaml file to build Interchain-queries
      default_chain: STRIDE-TESTNET-2
      chains:
        GAIA:
          key: gaiaRPC
          chain-id: GAIA
          rpc-addr: http://154.12.229.177:26957
          grpc-addr: http://154.12.229.177:9490
          account-prefix: cosmos
          keyring-backend: test
          gas-adjustment: 1.2
          gas-prices: 1uatom
          key-directory: /root/.icq/keys
          debug: false
          timeout: 20s
          block-timeout: ""
          output-format: json
          sign-mode: direct
        STRIDE-TESTNET-2:
          key: stride160
          chain-id: STRIDE-TESTNET-2
          rpc-addr: http://localhost:26957
          grpc-addr: http://localhost:9490
          account-prefix: stride
          keyring-backend: test
          gas-adjustment: 1.2
          gas-prices: 1ustrd
          key-directory: /root/.icq/keys
          debug: false
          timeout: 20s
          block-timeout: ""
          output-format: json
          sign-mode: direct
      cl: {}
