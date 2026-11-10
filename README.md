# fortress-bundle

Verified tool and data bundle for the Phone Fortress and Email Fortress bots.

The Fortress bot templates download `fortress-bundle-1.2.0.tar` from the `v1.2.0` tag. Before installing anything, they check its SHA-256 fingerprint:

```
b2a27454907424bd135e7dee4b740a202240c474bf271850d2fa738c59617573  fortress-bundle-1.2.0.tar
```

If the file doesn't match, isn't found, or redirects anywhere, the installer refuses it and installs nothing. Released versions are never changed. A new version gets a new file and a new tag.
