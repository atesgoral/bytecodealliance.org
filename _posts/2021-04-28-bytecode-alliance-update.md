---
title: "As WebAssembly grows in popularity, the Bytecode Alliance opens to new members"
author: "Till Schneidereit on behalf of the Board of Directors"
github_name: tschneidereit
---

The Bytecode Alliance has always set sights high on a goal of introducing new foundations for building software. Today, our work toward this goal is entering a new phase: we’re happy to [announce](/press/growing-the-bytecode-alliance) the incorporation of the Bytecode Alliance as a 501(c)(6) nonprofit organization and that we are opening up membership broadly. Starting with [Arm](https://www.arm.com/), [DFINITY Foundation](https://dfinity.org/), [Embark Studios](https://www.embark-studios.com/), [Google](https://research.google.com/), [Shopify](https://shopify.engineering/), and [University of California at San Diego](https://ucsd.edu/), we’re excited to welcome new collaborators and truly work together on a cross-industry effort to establish the right foundations for building secure and fast software at scale.

## Progress on Bytecode Alliance priorities
A lot has changed since we laid out our vision in our [initial announcement](/articles/announcing-the-bytecode-alliance). We’ve made [significant progress](/articles/1-year-update) on our core projects and helped drive the standardization of key proposals supporting the nanoprocess vision, including [WASI](https://github.com/WebAssembly/WASI), [Interface Types](https://github.com/WebAssembly/interface-types/blob/master/proposals/interface-types/Explainer.md), and [Module Linking](https://github.com/WebAssembly/module-linking/blob/master/proposals/module-linking/Explainer.md), as well as proposals, like [WASI-nn](https://github.com/WebAssembly/wasi-nn/blob/main/docs/Explainer.md) and [WASI-Crypto](https://github.com/WebAssembly/WASI-crypto), that open up new use cases. Additionally, we created [Wasmtime](https://wasmtime.dev/) embeddings for [Go](https://github.com/bytecodealliance/wasmtime-go), [Python](https://github.com/bytecodealliance/wasmtime-py/), and [.Net](https://github.com/bytecodealliance/wasmtime-dotnet/), and are getting close to wrapping up our [project to merge](https://www.fastly.com/blog/how-lucet-wasmtime-make-stronger-compiler-together) the [Lucet](https://www.fastly.com/blog/announcing-lucet-fastly-native-webassembly-compiler-runtime) and Wasmtime runtimes.

We’ve also created a new code-generation backend for the Cranelift WebAssembly compiler with a strong focus on performance and security. This new backend, created in close collaboration between Fastly, Mozilla, Intel, and Arm, [is now the default](https://github.com/bytecodealliance/rfcs/pull/10) for Wasmtime and Lucet, and Fastly recently ran a full security assessment of this critical technology and switched to this new backend for [Compute@Edge](https://www.fastly.com/products/edge-compute/serverless/).

And we’ve improved our processes for collaboration; for example, we introduced an [RFC process](https://github.com/bytecodealliance/rfcs/) to raise visibility and enable focused discussion of major changes to our core projects.

## Changes in context
But a lot has changed in the larger world, too. Since our founding, WebAssembly has seen critical gains in popularity and adoption rates. There are multiple WebAssembly conferences and events this year including last week’s [WebAssembly Summit 2021](https://webassembly-summit.org/), [Wasm Day](https://events.linuxfoundation.org/cloud-native-wasm-day/) during next week’s [Kubecon](https://events.linuxfoundation.org/kubecon-cloudnativecon-europe/), and a WebAssembly track at [QCon Plus 2021](https://plus.qconferences.com/?gclid%3DCjwKCAjw07qDBhBxEiwA6pPbHhLjoKucj_78gZ5wk5Vn22WybOUHdyqahRZnUafN-J9RZzWvHVj5ehoCWQkQAvD_BwE), May 17-28. We now see WebAssembly being used in production across the ecosystem and being leveraged as a critical, secure, and performant foundation for computing. The Bytecode Alliance is a space for the community to come together and continue to build this foundation. In doing so, major organizations are finding opportunities to use this technology at scale, and in security critical environments with the confidence needed to really realize the potential.

Some other changes mean that our mission is more important than ever. In describing the [nanoprocess vision](/articles/announcing-the-bytecode-alliance), we warned about the weaknesses inherent in the prevailing models of building software, which rely heavily on composing dozens, hundreds, or sometimes even thousands of third-party modules and libraries, without security boundaries between them. Since then, [weaknesses](https://www.dni.gov/files/NCSC/documents/supplychain/Software_Supply_Chain_Attacks.pdf) in the software supply chain [have been used](https://en.wikipedia.org/wiki/Supply_chain_attack) to breach the systems of governments, critical infrastructure services, and an astoundingly large number of companies. They were instrumental in stealing personal information of hundreds of millions, perhaps even billions of people.

Solving these challenges will require efforts across many industries, and not all aspects of any realistic solution are in scope for the Bytecode Alliance. But better answers to software composition are on the critical path for all of them, and as we open up to new members, the scope of collaboration with the Bytecode Alliance is still focused on developing solutions in this space, as defined by our [mission](/mission).

## Governance
We’ve spent a lot of time figuring out how to build a healthy and robust community where we have organizations building on and contributing to this ecosystem. We also want individual contributors for Bytecode Alliance projects strongly represented. The goal is that our governance has strong representation in both of these areas. Our [bylaws](/assets/bylaws.pdf) provide for direct community representation on the Board, and dictate that all changes to the bylaws themselves and the charter require community buy-in. In designing the rules around this, we’ve been following and building on best practices as defined by highly successful communities like the [OpenJS Foundation](https://openjsf.org/) that have spearheaded strong community representation in governance.

## Bootstrapping
We’re now [welcoming](/membership) new members to the Bytecode Alliance on a rolling basis. In parallel to onboarding additional members, over the next few months we’ll fully define a charter for a Technical Steering Committee (TSC), as well as the Board as part of a bootstrapping period. At the end of that period, we will organize Board and TSC elections to fully establish the Bytecode Alliance’s open governance model. More details to come in the near future. As we focus on scaling project scope and expanding the Alliance, we are excited to start supporting more hosted projects and we will share more information on our blog about additional activities and projects in the pipeline and within scope.

[Reach out](mailto:membership@bytecodealliance.org) if you’re interested in [joining](/membership) the Bytecode Alliance and contributing to our vision.