Verified tool and data bundle for the Phone Fortress and Email Fortress bots.

The 1.2.10 tools package is `fortress-bundle-1.2.10.tar` on the `v1.2.10` tag. It is the 1.2.0 bundle plus every 1.2.1–1.2.10 data change. Before installing anything, the bots check its SHA-256 fingerprint:

```
227e282de94ac95fec02226f456f30e3d96e3377676b5207e22c55e8d9ef0af6  fortress-bundle-1.2.10.tar
```

The original 1.2.0 package remains on the `v1.2.0` tag, unchanged:

```
b2a27454907424bd135e7dee4b740a202240c474bf271850d2fa738c59617573  fortress-bundle-1.2.0.tar
```

If the file doesn't match, isn't found, or redirects anywhere, the installer refuses it and installs nothing. Released versions are never changed. A new version gets a new file and a new tag.
