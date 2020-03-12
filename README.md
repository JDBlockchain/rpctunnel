# Web3 RPC proxy 

Test project that serves a RPC proxy.

# Usage

*   Install dependencies

    ```sh
    npm install
    ```

*   Configure by editing `config.js`. Set `rpcUrl` to the RPC URL you would like to proxy to. Set `port` to any available port. Set `limit` to your expected respone/request size.

    Example:
    ```
    module.exports = [{
        rpcUrl: 'http://127.0.0.1:8545',
        port: 7545,
        limit: '50kb'
    }];
    ```

*   Start server

    ```sh
    npm run start
    ```
