# Bundle Protocol (BP) Manifest Block

The internet-draft is hosted at [draft-sipos-dtn-manifest-block](https://datatracker.ietf.org/doc/draft-sipos-dtn-manifest-block/).

A local build of the current main branch is available [draft-sipos-dtn-manifest-block.html](https://briansipos.github.io/dtn-manifest-block/draft-sipos-dtn-manifest-block.html) with its [misspelling.txt](https://briansipos.github.io/dtn-manifest-block/misspelling.txt).
A difference from the datatracker draft and this local version can be [viewed side-by-side](https://author-tools.ietf.org/diff?doc_1=draft-sipos-dtn-manifest-block&url_2=https://briansipos.github.io/dtn-manifest-block/draft-sipos-dtn-manifest-block.txt&raw=1).

Prerequisites to building can be installed on Ubuntu with:
```
sudo apt-get install -y cmake python3 python3-pip python3-setuptools python3-wheel ruby xmlstarlet aspell cargo
pip3 install xml2rfc
sudo gem install cbor-diag
sudo cargo install --root /usr/local cddl
```

Then the document can be built with
```
cmake -S . -B build/default
cmake --build build/default
```

# Demo Convergence Layer Agent

The demo agent is in a separate project [dtn-demo-agent](https://github.com/BrianSipos/dtn-demo-agent).

# Wireshark Protocols and Dissectors

The wireshark modules are in a separate project [dtn-wireshark](https://github.com/BrianSipos/dtn-wireshark).
