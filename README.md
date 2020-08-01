# TANGLED_nomad_verfploeter

ORIGIN: https://dacs-git.ewi.utwente.nl/bertholdolm/nomad_verfploeter

archive referred to NOMAD download VERFPLOETER on Tangled site

To deploy a new version you need:

- Install nomad in your machine ( brew install nomad )
- Update nomad_verfploter in a local file ( vi nomad_verfploter )
- Connect your NOMAD to TestBED-NOMAD ( ssh -L 4646:10.8.0.1:4646 testbed@anycast-master )
- Run nomad ( nomad run ./verfploeter.nomad )
- Check new version (./verfploeter cli client-list)
