---
title: "Network-aware Demand Response in the Presence of Uncertainties"
collection: publications
permalink: /publication/PhD_thesis
excerpt: 'This PhD thesis develops network-aware residential demand response schemes in the presence of uncertainties.'
date: 2023-08-03
venue: 'UQ eSpace'
paperurl: 'https://doi.org/10.14264/0b87703'
citation: 'G. Lankeshwara, &quot;Network-aware Demand Response in the Presence of Uncertainties,&quot; 2023, doi:10.14264/0b87703'
---

**Abstract:** With the rapid proliferation of highly intermittent renewable energy sources in the electricity generation mix, grid operators face immense challenges in maintaining secure and reliable grid operation. To this end, demand response (DR) is a promising consumer-centric technique that has gained popularity with recent developments in two-way communication between end-users and the grid. However, challenges still exist when a cohort of end-users participate in electricity market services via a DR aggregator in a practical setting. For instance, there is no guarantee that the aggregator will be able to deliver the desired DR in real-time in the presence of unavoidable uncertainties, which will lead to financial penalties from the market operator. In addition, due to the lack of coordination between the DR aggregator and the distribution network service provider (DNSP), market-oriented residential DR schemes often lead to network statutory limit violations in low-voltage (LV) distribution networks.

This thesis aims to fill the gap and develop network-aware residential DR schemes in the presence of uncertainties. Firstly, centralised heuristic algorithms are proposed for end-user thermostatically controllable loads (TCLs) to provide DR in grid services in the presence of uncertainty factors such as end-user non-compliance, end-user thermal comfort violations and load set-point changes. Secondly, a centralised robust model predictive control (MPC) scheme is developed for residential air-conditioners (ACs) to provide regulation services in the presence of uncertainties due to model parameter mismatches and outdoor temperature forecast errors. Furthermore, the proposed schemes explicitly account for the operation of TCLs under existing DR standards in Australia. Thirdly, end-user privacy-preserving, distributed control schemes based on the Alternating Direction Method of Multipliers (ADMM) method, Lagrangian Relaxation (LR) and robust MPC are proposed for residential ACs to provide DR in real-time markets without compromising end-user thermal comfort. Moreover, these approaches account for uncertainties in outdoor temperature forecast errors and model parameter mismatches.

In the next stage, two novel techniques are introduced for a DNSP to establish dynamic operating envelopes (DOEs) to coordinate distributed energy resources (DERs) without jeopardising the safe operation of the LV distribution network. These include dynamic active power export limits for photovoltaic (PV) customers via an AC optimal power flow (OPF) scheme, an online approach to determine household DOEs, which account for active-reactive and import-export power limits and outline the feasible operating region (FOR) at the connection point. Finally, a real-time coordinated control scheme is developed for residential ACs to provide DR via an aggregator while adopting the proposed DOE framework for the DNSP.

All simulation validations in this thesis are performed on a practical LV residential network using realistic profiles for load and generation. Furthermore, a software-in-the-loop (SIL) validation is carried out in the real-time digital simulator (RTDS) platform to determine the efficacy of the proposed DOE-enabled residential DR scheme in satisfying network technical limits during real-time operation.

The research presented in this thesis confirms that through effective uncertainty mitigation techniques, DR can provide the desired level of performance in grid services while meeting end-user requirements. It also identified that with adequate coordination between the DNSP and the DR aggregator, the DOE framework can be effectively utilised to provide residential DR without breaching the technical limits of LV distribution networks. These findings represent a further step towards achieving greater market efficiency for the DR aggregator under high levels of network efficiency for the DNSP.



