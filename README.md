# Omi Rust Protocols

Beta Project


Rust message parsers generated from compiled binary data models — one crate per protocol version. Each crate's `borrowed` module holds zero-copy views over the packet buffer and its packet walkers; its `owned` module (feature `owned`, on by default) holds every message decoded into owned values, built from the views.


## Crates


- [Cme.Globex.Derived.Sbe.v12.0](Cme/Globex/Derived.Sbe/v12.0) — `cme-globex-derived-sbe-v12-0`
- [Cme.Globex.Mdp3.Sbe.v1.10](Cme/Globex/Mdp3.Sbe/v1.10) — `cme-globex-mdp3-sbe-v1-10`
- [Cme.Globex.Mdp3.Sbe.v1.11](Cme/Globex/Mdp3.Sbe/v1.11) — `cme-globex-mdp3-sbe-v1-11`
- [Cme.Globex.Mdp3.Sbe.v1.12](Cme/Globex/Mdp3.Sbe/v1.12) — `cme-globex-mdp3-sbe-v1-12`
- [Cme.Globex.Mdp3.Sbe.v1.13](Cme/Globex/Mdp3.Sbe/v1.13) — `cme-globex-mdp3-sbe-v1-13`
- [Cme.Globex.Mdp3.Sbe.v1.5](Cme/Globex/Mdp3.Sbe/v1.5) — `cme-globex-mdp3-sbe-v1-5`
- [Cme.Globex.Mdp3.Sbe.v1.6](Cme/Globex/Mdp3.Sbe/v1.6) — `cme-globex-mdp3-sbe-v1-6`
- [Cme.Globex.Mdp3.Sbe.v1.8](Cme/Globex/Mdp3.Sbe/v1.8) — `cme-globex-mdp3-sbe-v1-8`
- [Cme.Globex.Mdp3.Sbe.v1.9](Cme/Globex/Mdp3.Sbe/v1.9) — `cme-globex-mdp3-sbe-v1-9`
- [Cme.Globex.Settlements.Sbe.v7.0](Cme/Globex/Settlements.Sbe/v7.0) — `cme-globex-settlements-sbe-v7-0`
- [Cme.Globex.Streamlined.Sbe.v5.8](Cme/Globex/Streamlined.Sbe/v5.8) — `cme-globex-streamlined-sbe-v5-8`
- [Cme.Globex.Streamlined.Sbe.v5.9](Cme/Globex/Streamlined.Sbe/v5.9) — `cme-globex-streamlined-sbe-v5-9`
- [Cme.Globex.iLink3.Sbe.v8.2](Cme/Globex/iLink3.Sbe/v8.2) — `cme-globex-ilink3-sbe-v8-2`
- [Cme.Globex.iLink3.Sbe.v8.3](Cme/Globex/iLink3.Sbe/v8.3) — `cme-globex-ilink3-sbe-v8-3`
- [Cme.Globex.iLink3.Sbe.v8.4](Cme/Globex/iLink3.Sbe/v8.4) — `cme-globex-ilink3-sbe-v8-4`
- [Cme.Globex.iLink3.Sbe.v8.5](Cme/Globex/iLink3.Sbe/v8.5) — `cme-globex-ilink3-sbe-v8-5`
- [Cme.Globex.iLink3.Sbe.v8.6](Cme/Globex/iLink3.Sbe/v8.6) — `cme-globex-ilink3-sbe-v8-6`
- [Cme.Globex.iLink3.Sbe.v8.7](Cme/Globex/iLink3.Sbe/v8.7) — `cme-globex-ilink3-sbe-v8-7`
- [Cme.Globex.iLink3.Sbe.v8.8](Cme/Globex/iLink3.Sbe/v8.8) — `cme-globex-ilink3-sbe-v8-8`
- [Cme.Globex.iLink3.Sbe.v8.9](Cme/Globex/iLink3.Sbe/v8.9) — `cme-globex-ilink3-sbe-v8-9`
- [Databento.MarketData.Normalized.Dbn.v1](Databento/MarketData/Normalized.Dbn/v1) — `databento-marketdata-normalized-dbn-v1`
- [Databento.MarketData.Normalized.Dbn.v2](Databento/MarketData/Normalized.Dbn/v2) — `databento-marketdata-normalized-dbn-v2`
- [Databento.MarketData.Normalized.Dbn.v3](Databento/MarketData/Normalized.Dbn/v3) — `databento-marketdata-normalized-dbn-v3`
- [Nasdaq.IseOptions.OrderComboFeed.Itch.v1.1](Nasdaq/IseOptions/OrderComboFeed.Itch/v1.1) — `nasdaq-iseoptions-ordercombofeed-itch-v1-1`
- [Nasdaq.IseOptions.TopComboQuoteFeed.Itch.v1.0](Nasdaq/IseOptions/TopComboQuoteFeed.Itch/v1.0) — `nasdaq-iseoptions-topcomboquotefeed-itch-v1-0`
- [Nasdaq.NsmEquities.NlsPlus.Itch.v4.0](Nasdaq/NsmEquities/NlsPlus.Itch/v4.0) — `nasdaq-nsmequities-nlsplus-itch-v4-0`
- [Nasdaq.NsmEquities.Orders.Ouch.v4.2.2018](Nasdaq/NsmEquities/Orders.Ouch/v4.2.2018) — `nasdaq-nsmequities-orders-ouch-v4-2-2018`
- [Nasdaq.NsmEquities.Orders.Ouch.v4.2.2025](Nasdaq/NsmEquities/Orders.Ouch/v4.2.2025) — `nasdaq-nsmequities-orders-ouch-v4-2-2025`
- [Nasdaq.NsmEquities.Orders.Ouch.v5.0](Nasdaq/NsmEquities/Orders.Ouch/v5.0) — `nasdaq-nsmequities-orders-ouch-v5-0`
- [Nasdaq.NsmEquities.TotalView.Itch.v4.1](Nasdaq/NsmEquities/TotalView.Itch/v4.1) — `nasdaq-nsmequities-totalview-itch-v4-1`
- [Nasdaq.NsmEquities.TotalView.Itch.v5.0.2017](Nasdaq/NsmEquities/TotalView.Itch/v5.0.2017) — `nasdaq-nsmequities-totalview-itch-v5-0-2017`
- [Nasdaq.NsmEquities.TotalView.Itch.v5.0.2023](Nasdaq/NsmEquities/TotalView.Itch/v5.0.2023) — `nasdaq-nsmequities-totalview-itch-v5-0-2023`
- [Nasdaq.NtxEquities.Orders.Ouch.v4.2](Nasdaq/NtxEquities/Orders.Ouch/v4.2) — `nasdaq-ntxequities-orders-ouch-v4-2`
- [Nasdaq.NtxEquities.TotalView.Itch.v5.0](Nasdaq/NtxEquities/TotalView.Itch/v5.0) — `nasdaq-ntxequities-totalview-itch-v5-0`
- [Nasdaq.PsxEquities.Orders.Ouch.v4.2](Nasdaq/PsxEquities/Orders.Ouch/v4.2) — `nasdaq-psxequities-orders-ouch-v4-2`
- [Nasdaq.PsxEquities.TotalView.Itch.v5.0](Nasdaq/PsxEquities/TotalView.Itch/v5.0) — `nasdaq-psxequities-totalview-itch-v5-0`
