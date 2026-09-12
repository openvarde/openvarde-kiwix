# openvarde-kiwix

Installs the official Kiwix project and provides access via OpenVarde system. This gives the capability to download Wikipedia and other resources for complete offline usage.

**OpenVarde** is an open-source, modular platform for building resilient and offline-capable information systems for preparedness and emergency use.

## Features

* Provides offline Kiwix-reader feature
* Download Wikipedia and other resources for offline browsing

## Integration

This module integrates with OpenVarde through:

* **HTTP:** `http://openvarde-[short-id].local/kiwix`
* **Dependencies:** `openvarde-core`

## Getting started

### Requirements

* Docker
* Docker Compose
* openvarde-core

### Run

```bash id="ht13no"
git clone https://github.com/openvarde/openvarde-kiwix.git
cd openvarde-kiwix
docker compose up -d
```

View logs:

```bash id="k9md4g"
docker compose logs -f
```

## Configuration

No configuration available yet.

## Discussion & contributing

OpenVarde is under active development. Testing, bug reports, documentation improvements and code contributions are welcome.

For bugs and concrete development tasks, please use GitHub Issues.

For questions, ideas and general discussion, visit the [OpenVarde thread on Norsk Beredskapsforum](https://norskberedskapsforum.no/topic/1871-prosjekt-openvarde-åpen-og-modulær-beredskaps-pc-for-bruk-med-og-uten-internett/).

## AI disclosure

AI-assisted tools are used in the development of OpenVarde, including code, documentation and technical problem solving. AI-assisted contributions are reviewed and treated as development input, not authoritative output.

## License

See `LICENSE` for licensing information.
