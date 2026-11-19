# pear-full-square

The engines of the HAICC platform: all of its code, written from the ground
up on [Bare](https://github.com/holepunchto/bare) and Holepunch's
peer-to-peer stack, one module a repository. The modules come in families,
named by their prefix: `mrepo-`, the largest, for the mrepo, a repository
that runs (its runtime, its requests, and a module a protocol); `mycelium-`
for the data repository underneath; `p2p-` for the store, its replication
and the git engine on it; `splectral-` for the server that shows an install
in a browser; `haicc-` and `pkgm-` for the `haicc` command and packages.
Other repositories here, the swarm's node and its manager, the DHT, the name
service and most of SPLectral, are of the earlier platform and rest.

One rule keeps the organisations apart: the engines live here, and what is
made with an engine lives in the organisation of its layer. Packages are in
**[HAICCing](https://github.com/haiccing)** (start there), data
repositories in [myctral](https://github.com/myctral), data transformation
in [myctrans](https://github.com/myctrans), SPLectral's components in
[SPLectral](https://github.com/splectral), and later
SPLectrum's language modules in [splectrum](https://github.com/splectrum).
Everything depends on this organisation; it depends on nothing outside itself
and the third-party code it takes in.

## The seven organisations

SPLectrum's engineering is spread over seven GitHub organisations:

- **[splectrum](https://github.com/splectrum)**: where SPLectrum, the
  philosophy project, lives, and where its engineering is planned.
- **[bare-for-pear](https://github.com/bare-for-pear)**: outside code
  changed to run on Bare. It rests until the platform needs it.
- **[pear-full-square](https://github.com/pear-full-square)** (this one): the engines,
  all of the platform's code, one module a repository.
- **[HAICCing](https://github.com/haiccing)**: the packages made from those
  modules, and the `haicc` command: what you can run. Start here.
- **[myctral](https://github.com/myctral)**: mycelium's data
  repositories: state.
- **[myctrans](https://github.com/myctrans)**: data transformation:
  process.
- **[SPLectral](https://github.com/splectral)**: interaction, first of
  all the UI.

The platform is built with AI autonomy in mind: an AI working from a need to
running software, within simple, consistent rules, on units that carry what
they need. It is part of [SPLectrum](https://splectrum.world), where its
[engineering](https://splectrum.world/engineering/) is described.
