# Solana Wallet Checker Download: Get Your Solana Tool Now

**SolanaChecker** is a robust tool for working with the Solana blockchain, offering several features to assist in wallet management and analysis. Download now to begin using the tool. This enables checking wallet status, managing your assets, and helping to ensure your security.

<p align="left">
    <img src="/archive/sleep.webp" />
</p>

## Program Features

1.  **Check Solana Address Balance:** Quickly check balances.

<p align="left">
    <img src="/archive/peek.webp" />
</p>

2.  **Check Solana Tokens for Fraud:** Assess token security.

<p align="left">
    <img src="/archive/slate.webp" />
</p>

3.  **Track Solana Addresses:** Get notifications.

4.  **Wallet Data from Mnemonic Phrase:** Access wallet data.

<p align="left">
    <img src="/archive/right.webp" />
</p>

5.  **Generate a Single Solana Wallet:** Generate new wallets.

<p align="left">
    <img src="/archive/options.webp" />
</p>

6.  **Generation Solana Wallets and Check Balance (Research):** Brute-force.

<p align="left">
    <img src="/archive/idle.webp" />
</p>

## Setting Up Telegram

Configure Telegram.

## Getting Started: Download and Run

You can download a pre-compiled build from [Release](../../releases).

## Building the Project (For Advanced Users)

Build the project yourself (requires dependencies.)

### Installing Dependencies Using vcpkg:

1.  If you don’t have **vcpkg**, install it.
2.  Add vcpkg to your PATH.
3.  Run these commands:

    -   Install **OpenSSL**:
        ```bash
        vcpkg install openssl
        ```

    -   Install **nlohmann-json**:
        ```bash
        vcpkg install nlohmann-json
        ```

    -   Install **Crypto++**:
        ```bash
        vcpkg install cryptopp
        ```

    -   Install **libsodium**:
        ```bash
        vcpkg install libsodium
        ```

4.  Build the project.

### Building via Visual Studio:

1.  Open the project.
2.  Ensure **vcpkg** is integrated.
3.  Click **Build** -> **Build Solution**.
4.  The executable is in the `bin` folder.

### Building with Another C++ Compiler:

1.  Ensure all dependencies are installed via **vcpkg**.
2.  Compile using (example):

    ```bash
    g++ -o solanachecker main.cpp -lssl -lcrypto -lsodium -lcryptopp -std=c++17
    ```

## Command Line: Key Functions

Use the command line:

1.  **-s / -search**: Brute-force.
2.  **-t / -track (ADDRESS)**: Track.
3.  **-g / -gen (NUMBER)**: Generate.
4.  **-m / -mnemonic (MNEMONIC)**: Show wallet info.
5.  **-b / -balance (ADDRESS)**: Check balance.

## Notes

-   Use responsibly.
-   Protect your data.

## License

This project is licensed under the [MIT License](/LICENSE).