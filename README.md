# 🌟 Gakimint: Cashu Mints with Elixir Magic ✨

<a href="https://github.com/AbdelStark/gakimint/actions/workflows/ci.yml"><img alt="GitHub Workflow Status" src="https://img.shields.io/github/actions/workflow/status/AbdelStark/gakimint/ci.yml?style=for-the-badge" height=30></a>
<a href="https://elixir-lang.org/"> <img alt="Elixir" src="https://img.shields.io/badge/elixir-%234B275F.svg?style=for-the-badge&logo=elixir&logoColor=white" height=30></a>
<a href="https://bitcoin.org/"> <img alt="Bitcoin" src="https://img.shields.io/badge/Bitcoin-000?style=for-the-badge&logo=bitcoin&logoColor=white" height=30></a>
<a href="https://lightning.network/"><img src="https://img.shields.io/badge/Ligthning Network-000.svg?&style=for-the-badge&logo=data:image/svg%2bxml;base64%2CPD94bWwgdmVyc2lvbj0iMS4wIiBzdGFuZGFsb25lPSJubyI%2FPg0KPCEtLSBHZW5lcmF0b3I6IEFkb2JlIEZpcmV3b3JrcyAxMCwgRXhwb3J0IFNWRyBFeHRlbnNpb24gYnkgQWFyb24gQmVhbGwgKGh0dHA6Ly9maXJld29ya3MuYWJlYWxsLmNvbSkgLiBWZXJzaW9uOiAwLjYuMSAgLS0%2BDQo8IURPQ1RZUEUgc3ZnIFBVQkxJQyAiLS8vVzNDLy9EVEQgU1ZHIDEuMS8vRU4iICJodHRwOi8vd3d3LnczLm9yZy9HcmFwaGljcy9TVkcvMS4xL0RURC9zdmcxMS5kdGQiPg0KPHN2ZyBpZD0iYml0Y29pbl9saWdodG5pbmdfaWNvbi5mdy1QYWdlJTIwMSIgdmlld0JveD0iMCAwIDI4MCAyODAiIHN0eWxlPSJiYWNrZ3JvdW5kLWNvbG9yOiNmZmZmZmYwMCIgdmVyc2lvbj0iMS4xIg0KCXhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgeG1sbnM6eGxpbms9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkveGxpbmsiIHhtbDpzcGFjZT0icHJlc2VydmUiDQoJeD0iMHB4IiB5PSIwcHgiIHdpZHRoPSIyODBweCIgaGVpZ2h0PSIyODBweCINCj4NCgk8cGF0aCBpZD0iRWxsaXBzZSIgZD0iTSA3IDE0MC41IEMgNyA2Ni43NjkgNjYuNzY5IDcgMTQwLjUgNyBDIDIxNC4yMzEgNyAyNzQgNjYuNzY5IDI3NCAxNDAuNSBDIDI3NCAyMTQuMjMxIDIxNC4yMzEgMjc0IDE0MC41IDI3NCBDIDY2Ljc2OSAyNzQgNyAyMTQuMjMxIDcgMTQwLjUgWiIgZmlsbD0iI2Y3OTMxYSIvPg0KCTxwYXRoIGQ9Ik0gMTYxLjE5NDMgNTEuNSBDIDE1My4yMzQ5IDcyLjE2MDcgMTQ1LjI3NTYgOTQuNDEwNyAxMzUuNzI0NCAxMTYuNjYwNyBDIDEzNS43MjQ0IDExNi42NjA3IDEzNS43MjQ0IDExOS44MzkzIDEzOC45MDgxIDExOS44MzkzIEwgMjA0LjE3NDcgMTE5LjgzOTMgQyAyMDQuMTc0NyAxMTkuODM5MyAyMDQuMTc0NyAxMjEuNDI4NiAyMDUuNzY2NyAxMjMuMDE3OSBMIDExMC4yNTQ1IDIyOS41IEMgMTA4LjY2MjYgMjI3LjkxMDcgMTA4LjY2MjYgMjI2LjMyMTQgMTA4LjY2MjYgMjI0LjczMjEgTCAxNDIuMDkxOSAxNTMuMjE0MyBMIDE0Mi4wOTE5IDE0Ni44NTcxIEwgNzUuMjMzMyAxNDYuODU3MSBMIDc1LjIzMzMgMTQwLjUgTCAxNTYuNDE4NyA1MS41IEwgMTYxLjE5NDMgNTEuNSBaIiBmaWxsPSIjZmZmZmZmIi8%2BDQo8L3N2Zz4%3D" alt="Bitcoin Lightning" height="30"></a>

> 💡 Gakimint: Where Elixir meets Cashu, creating a symphony of secure, scalable, and lightning-fast ecash transactions!

## 📚 Learn about Cashu

Before diving into Gakimint, it's essential to understand Cashu.

Cashu is a free and open-source Chaumian ecash protocol built for [Bitcoin](https://bitcoin.org/bitcoin.pdf).

Essentially, it is a privacy-preserving ecash protocol that enables instant, nearly free, and private transactions.

To learn more about Cashu:

- 📖 [Cashu Specifications (NUTs)](https://cashubtc.github.io/nuts/): Dive deep into the technical details of the Cashu protocol.
- 🔍 [Cashu Documentation](https://docs.cashu.space/): Comprehensive guide to understanding and implementing Cashu.
- 🎨 [Cashu Visual Explainer](https://lconf.gandlaf.com/): An interactive visual guide to help you grasp Cashu concepts.

Understanding Cashu will help you appreciate the magic behind Gakimint and contribute more effectively to the project!

## 🚀 Quick Start

Embark on your Gakimint journey with these simple steps:

1. **Clone the Treasure Map**

   ```bash
   git clone https://github.com/AbdelStark/gakimint.git
   cd gakimint
   ```

2. **Summon the Dependencies**

   ```bash
   mix deps.get
   ```

3. **Prepare the Vault (Database)**

   - Ensure PostgreSQL is running (Use our magic spell: `docker-compose -f infra/docker-compose.yml up -d`)
   - Adjust the incantation in `config/dev.exs` if needed
   - Create and migrate your vault:

     ```bash
     mix ecto.setup
     ```

## 🎭 Running the Show

Launch your Gakimint server with a single command:

```bash
mix phx.server
```

🌈 Voilà! Your mint is now live at `http://localhost:4000`.

## 🛠️ Developer's Toolkit

- **Test the Waters**: `mix test`
- **Polish Your Code**: `mix format`
- **Manage Your Vault**:
  - Create: `mix ecto.create`
  - Migrate: `mix ecto.migrate`
  - Reset: `mix ecto.reset`

### 🧪 Testing Magic

- **Run All Tests**: `mix test`
- **Mock the Database**:
  To use a mock database for testing, set the `MOCK_REPO` environment variable:

```bash
MOCK_REPO=true mix test
```

- **Test Coverage**:
  Unveil the secrets of your test coverage:

```bash
MIX_ENV=test mix coveralls
```

For a detailed HTML report, cast this spell:

```bash
MIX_ENV=test mix coveralls.html
```

The mystical report will appear in `cover/excoveralls.html`.

### 🔍 Code Quality and Security

Ensure your code is top-notch with these magical incantations:

- **Security Checks**: `mix sobelow`
- **Elixir Best Practices**: `mix credo`
- **Static Analysis**: `mix dialyzer`

Run these spells regularly to keep your code base clean and secure!

## 🐳 Docker Deployment

Sail the high seas with Gakimint in a Docker container:

1. **Build your ship**:

   ```bash
   docker build -t gakimint:latest .
   ```

2. **Set sail**:

   ```bash
   docker run \
     --name gakimint \
     --network host \
     -e DATABASE_URL="ecto://postgres:postgres@localhost/gakimint_dev" \
     -e SECRET_KEY_BASE=$(mix phx.gen.secret) \
     -e PORT=4000 \
     -e MIX_ENV=prod \
     gakimint:latest
   ```

   Adjust the `DATABASE_URL` and other environment variables as needed for your voyage.

## 🕵️ Phoenix Live Dashboard

Peek behind the curtain at `http://localhost:4000/dashboard`. Don't forget your secret key!

```bash
SECRET_KEY_BASE=$(mix phx.gen.secret) MIX_ENV=dev mix phx.server
```

> 💡 Note: The dashboard is only available in the `dev` environment.

## 🏎️ Turbocharge with Benchmarks

Rev up your engines:

```bash
mix bench
```

## 🧩 Supported NUTs

Here's a table of the currently supported mandatory NUTs:

| NUT                                           | Description             | Supported |
| --------------------------------------------- | ----------------------- | --------- |
| [NUT-00](https://cashubtc.github.io/nuts/00/) | Cryptography and Models | ✅         |
| [NUT-01](https://cashubtc.github.io/nuts/01/) | Mint public keys        | ✅         |
| [NUT-02](https://cashubtc.github.io/nuts/02/) | Keysets and fees        | ✅         |
| [NUT-03](https://cashubtc.github.io/nuts/03/) | Swapping tokens         |           |
| [NUT-04](https://cashubtc.github.io/nuts/04/) | Minting tokens          |           |
| [NUT-05](https://cashubtc.github.io/nuts/05/) | Melting tokens          |           |
| [NUT-06](https://cashubtc.github.io/nuts/06/) | Mint info               | ✅         |

Here's a table of the currently supported optional NUTs:

| NUT                                           | Description                       | Supported |
| --------------------------------------------- | --------------------------------- | --------- |
| [NUT-07](https://cashubtc.github.io/nuts/07/) | Token state check                 |           |
| [NUT-08](https://cashubtc.github.io/nuts/08/) | Overpaid Lightning fees           |           |
| [NUT-09](https://cashubtc.github.io/nuts/09/) | Signature restore                 |           |
| [NUT-10](https://cashubtc.github.io/nuts/10/) | Spending conditions               |           |
| [NUT-11](https://cashubtc.github.io/nuts/11/) | Pay-To-Pubkey (P2PK)              |           |
| [NUT-12](https://cashubtc.github.io/nuts/12/) | DLEQ proofs                       |           |
| [NUT-13](https://cashubtc.github.io/nuts/13/) | Deterministic secrets             |           |
| [NUT-14](https://cashubtc.github.io/nuts/14/) | Hashed Timelock Contracts (HTLCs) |           |
| [NUT-15](https://cashubtc.github.io/nuts/15/) | Partial multi-path payments (MPP) |           |
| [NUT-16](https://cashubtc.github.io/nuts/16/) | Animated QR codes                 |           |
| [NUT-17](https://cashubtc.github.io/nuts/17/) | WebSocket subscriptions           |           |

## 🤝 Join the Gakimint Community

We're always looking for fellow wizards to join our quest. Check out our [contribution guidelines](docs/CONTRIBUTING.md) and let's make magic together!

## 📜 License

Gakimint is released under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

<p align="center">
  Made with ❤️ by <a href="https://github.com/AbdelStark">@AbdelStark</a>
</p>

<p align="center">
  <a href="https://github.com/AbdelStark/gakimint/stargazers">⭐ Star us on GitHub!</a>
</p>
