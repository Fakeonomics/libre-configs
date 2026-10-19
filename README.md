# libre-configs

> **libre** ≠ gratis  
> **libre** = *liber* = *liberate* = *library*  
> **freedom** ≠ free beer. **freedom** = *liberty*.

---

## Main Config

| File | Description | Protocol |
|------|-------------|----------|
| [`liber`](liber) | Main config — all protocols | All |
| [`umbra`](by-protocol/umbra) | VLESS — invisible | VLESS |
| [`phantom`](by-protocol/phantom) | VMess — phantom | VMess |
| [`celeritas`](by-protocol/celeritas) | Hysteria2 — speed | Hysteria2 |
| [`equus`](by-protocol/equus) | Trojan — hidden | Trojan |

---

## By Region

| Region | File | Latin |
|--------|------|--------|
| Europe | [`europa`](by-region/europa) | *europa* |
| North America | [`septentrio`](by-region/septentrio) | *septentrio* |
| Asia | [`oriens`](by-region/oriens) | *oriens* |

---

## Special Builds

| File | Meaning | Latin |
|------|---------|-------|
| [`occultus`](special/occultus) | Stealth (Reality, gRPC) | *occultus* |
| [`lux`](special/lux) | Speed only | *lux* |
| [`anchor`](special/anchor) | Stable only | *anchor* |

---

## Usage

### In Client (Hiddify, v2rayNG, Nekobox, Sing-box)
```
https://raw.githubusercontent.com/Fakeonomics/libre-configs/main/liber
```

### VLESS Only
```
https://raw.githubusercontent.com/Fakeonomics/libre-configs/main/by-protocol/umbra
```

### Europe Only
```
https://raw.githubusercontent.com/Fakeonomics/libre-configs/main/by-region/europa
```

### Stealth Only (Reality, gRPC)
```
https://raw.githubusercontent.com/Fakeonomics/libre-configs/main/special/occultus
```

---

## Auto-Update
Every **30 minutes** from Fakeonomics VPN (`fakeonomics.online`).  
GitHub Actions → `main` branch → `raw.githubusercontent.com` (CDN, instant).

---

## Integrity
```bash
sha256sum -c checksums.sha256
```

---

## License
**Unlicense** — public domain.  
Do what you want. Freedom is libre.

---

> **libre** = *liber* = *liberate* = *library*  
> **not free as in beer. free as in liberty.**
