# Rivora Ecosystem

Open-source Python web ecosystem focused on modern web protocols.

Rivora is being built around the idea of keeping servers and frameworks independent through a common interface.

## Projects

### [RCP](https://github.com/RivoraEcosystem/RCP)

**Rivora Contract Protocol**

A communication protocol inspired by ASGI that allows compatible servers and frameworks to work together without depending on each other's internal implementation.

### [Riven](https://github.com/RivoraEcosystem/Riven)

**Python RCP-based application server**

Riven is the server side of the ecosystem, currently focused on building an HTTP/3 server using `aioquic`, `asyncio`, and `uvloop`.

### Rivora

**Web framework**

The framework layer of the ecosystem, designed to run through RCP.

Rivora is currently in the planning stage while development is focused on Riven.

## Development

The ecosystem is being built in public, with development logs, architecture decisions, experiments, and releases shared along the way.

Current focus:

`HTTP/3` · `QUIC` · `RCP` · `Python`

More projects and tooling will be added as the ecosystem grows.

---

Built as an open-source project by [Bhavya Malhotra](https://github.com/code-1py)
