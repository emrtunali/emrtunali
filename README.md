<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/svg/header-dark.svg">
  <img src="assets/svg/header-light.svg" width="100%" alt="Emir Tunalı · Data products, end to end. Forecasting, on-device ML, fintech, Istanbul.">
</picture>

<p align="center">
  <a href="https://www.linkedin.com/in/emir-tunal%C4%B1-4768571a3/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://apps.apple.com/tr/app/finsight-pro-simulation/id6757315007?l=tr"><img src="https://img.shields.io/badge/App_Store-FinSight_Pro-0D96F6?style=for-the-badge&logo=appstore&logoColor=white" alt="FinSight Pro on the App Store"></a>
  <a href="#selected-work"><img src="https://img.shields.io/badge/5_live_demos-5ee7c5?style=for-the-badge&logo=githubpages&logoColor=0b0d14" alt="Five live demos"></a>
</p>

## About

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/svg/about-dark.svg">
  <img src="assets/svg/about-light.svg" width="100%" alt="whoami: Emir Tunalı, software developer, Istanbul. Focus: forecasting, on-device ML, Turkish open data, fintech.">
</picture>

I like problems where the data is messy and the answer has to be right: tomorrow's electricity price, a delivery van in Istanbul traffic, a collapsed building in a satellite image, a bank statement full of shop names nobody has labelled.

My loop is usually the same. I find a public data source that nobody has cleaned up yet (EPİAŞ, İBB, KAP, Eurostat, OpenF1), build a model, and test it on data it has never seen against the best baseline that already exists. Then I ship it as something you can open in a browser, with a daily pipeline that keeps it current. Every README says where the model falls short, because a number you cannot check is not worth much.

I graduated first in my faculty at Istanbul Ticaret University, and I have shipped a market analysis app to the App Store.

<table>
<tr>
<td valign="top" width="33%"><b>Models</b><br><sub>forecasting · probabilistic & calibrated outputs · Monte Carlo · naive Bayes · CNNs · RAG</sub></td>
<td valign="top" width="33%"><b>Data</b><br><sub>Turkish open data · geospatial · time series · PDF and table extraction · daily pipelines</sub></td>
<td valign="top" width="33%"><b>Product</b><br><sub>dependency-free web apps · SVG charts · PWAs · Flutter · FastAPI · CI and tests</sub></td>
</tr>
</table>

## Selected work

<table>
<tr>
<td width="50%" valign="top">
<a href="https://github.com/emrtunali/kumbara"><img src="assets/projects/kumbara.png" alt="Kumbara: spending summary, personal inflation and savings rate"></a>
<h3><a href="https://github.com/emrtunali/kumbara">Kumbara</a></h3>
<sub><b>PERSONAL FINANCE · ON-DEVICE ML</b></sub>
<p>Bank statement analysis that never leaves the browser. A naive Bayes model trained in the browser categorises local shops that brand rules miss, and asks when it is unsure.</p>
<p><b>14 % → 79 %</b> correct on 121 unseen merchants · <b>97 %</b> precision when it commits · personal inflation · savings planner</p>
<a href="https://emrtunali.github.io/kumbara/?ornek"><img src="https://img.shields.io/badge/Live_demo-5ee7c5?style=flat-square" alt="Live demo"></a> <img src="https://img.shields.io/badge/JavaScript-PWA-1f2937?style=flat-square" alt="JavaScript, PWA">
</td>
<td width="50%" valign="top">
<a href="https://github.com/emrtunali/puant"><img src="assets/projects/puant.png" alt="Puant: tomorrow's hourly electricity price with its uncertainty band"></a>
<h3><a href="https://github.com/emrtunali/puant">Puant</a></h3>
<sub><b>ENERGY MARKETS · FORECASTING</b></sub>
<p>Day-ahead probabilistic forecasts of Turkish electricity prices, demand, wind, solar and carbon, with Shapley explanations and an auction simulator on EPİAŞ's real bids.</p>
<p>Beats TEİAŞ's load plan by <b>25 %</b> and EPİAŞ's wind forecast by <b>34 %</b> · a battery on it earns <b>82 %</b> of perfect foresight</p>
<a href="https://emrtunali.github.io/puant/"><img src="https://img.shields.io/badge/Dashboard-6aa8ff?style=flat-square" alt="Dashboard"></a> <img src="https://img.shields.io/badge/Python-scikit--learn-1f2937?style=flat-square" alt="Python, scikit-learn">
</td>
</tr>
<tr>
<td width="50%" valign="top">
<a href="https://github.com/emrtunali/rotaist"><img src="assets/projects/rotaist.jpg" alt="Rotaist: two planners replaying the same day on real Istanbul traffic"></a>
<h3><a href="https://github.com/emrtunali/rotaist">Rotaist</a></h3>
<sub><b>LOGISTICS · OPTIMISATION</b></sub>
<p>Tomorrow's street-level traffic forecast from İBB open data, fed into a time-dependent ALNS optimiser written from scratch, then driven on the traffic that really happened.</p>
<p><b>10–17 % fewer driver hours</b> than Google OR-Tools at the same punctuality · traffic error <b>3.5 km/h</b> vs 9.3</p>
<a href="https://emrtunali.github.io/rotaist/"><img src="https://img.shields.io/badge/Live_replay-6aa8ff?style=flat-square" alt="Live replay"></a> <img src="https://img.shields.io/badge/Python-numba_·_MapLibre-1f2937?style=flat-square" alt="Python, numba, MapLibre">
</td>
<td width="50%" valign="top">
<a href="https://github.com/emrtunali/pitwall"><img src="assets/projects/pitwall.png" alt="Pitwall: a 2026 Grand Prix replayed on the track map with live timing"></a>
<h3><a href="https://github.com/emrtunali/pitwall">Pitwall</a></h3>
<sub><b>SPORTS ANALYTICS · SIMULATION</b></sub>
<p>Every 2026 Formula 1 race rebuilt from raw timing data, with a live win probability, a strategy simulator and a tyre model. It updates itself after every race.</p>
<p>Tyre model <b>28 % lower error</b> than a flat-pace baseline on 9 unseen races · <b>380 / 380</b> championship points reconciled</p>
<a href="https://emrtunali.github.io/pitwall/"><img src="https://img.shields.io/badge/Live_demo-b48cff?style=flat-square" alt="Live demo"></a> <img src="https://img.shields.io/badge/Python-Three.js-1f2937?style=flat-square" alt="Python, Three.js">
</td>
</tr>
<tr>
<td width="50%" valign="top">
<a href="https://github.com/emrtunali/enkaz"><img src="assets/projects/enkaz.jpg" alt="Enkaz: before and after satellite crops with expert labels and model predictions"></a>
<h3><a href="https://github.com/emrtunali/enkaz">Enkaz</a></h3>
<sub><b>COMPUTER VISION · DISASTER RESPONSE</b></sub>
<p>Building-level damage from pre- and post-event satellite images of the 6 February 2023 earthquakes, tested on Antakya, a city kept out of training entirely.</p>
<p>The top 10 % of its ranking finds <b>51–55 %</b> of destroyed buildings (10 % for a change score) · calibrated probabilities</p>
<a href="https://emrtunali.github.io/enkaz/"><img src="https://img.shields.io/badge/Interactive_page-5ee7c5?style=flat-square" alt="Interactive page"></a> <img src="https://img.shields.io/badge/PyTorch-geospatial-1f2937?style=flat-square" alt="PyTorch, geospatial">
</td>
<td width="50%" valign="top">
<a href="https://github.com/emrtunali/kap-analyst"><img src="assets/projects/kap-analyst.svg" alt="KAP Analyst: a question about THY's 2024 net margin answered with tool calls and page citations"></a>
<h3><a href="https://github.com/emrtunali/kap-analyst">KAP Analyst</a></h3>
<sub><b>LLM AGENTS · RETRIEVAL</b></sub>
<p>Answers questions about Borsa İstanbul companies from their KAP filings, with page-level citations. Ratios come from extracted statement values, never from model arithmetic.</p>
<p>Retrieval Hit@5 <b>0.912</b> (BM25 alone 0.692) · Turkish questions <b>0.961</b> · <b>90 / 90</b> statement values exact</p>
<img src="https://img.shields.io/badge/Python-FastAPI_·_BGE--M3-1f2937?style=flat-square" alt="Python, FastAPI, BGE-M3">
</td>
</tr>
</table>

## Shipped

<table>
<tr>
<td width="190" valign="top"><img src="assets/finsight_dashboard.png" width="170" alt="FinSight Pro home dashboard"></td>
<td valign="top">
<h3><a href="https://apps.apple.com/tr/app/finsight-pro-simulation/id6757315007?l=tr">FinSight Pro Simulation</a></h3>
<sub><b>iOS · ANDROID · ON THE APP STORE</b></sub>
<p>Market analysis and paper trading. A Flutter client and a FastAPI backend with real-time WebSocket market data, portfolio risk and diversification analytics, ML and LLM market insights, and PDF reports. Educational simulation, no real money.</p>
<img src="https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white" alt="Flutter"> <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI"> <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL"> <img src="https://img.shields.io/badge/Firebase-DD2C00?style=flat-square&logo=firebase&logoColor=white" alt="Firebase">
</td>
</tr>
</table>

## Tools

<p>
  <img src="https://skillicons.dev/icons?i=python,pytorch,sklearn,fastapi,postgres,docker,githubactions,js,html,css,flutter,dart,swift,cs,dotnet,java,firebase,git&perline=9" alt="Python, PyTorch, scikit-learn, FastAPI, PostgreSQL, Docker, GitHub Actions, JavaScript, HTML, CSS, Flutter, Dart, Swift, C#, .NET, Java, Firebase, Git">
</p>

## Experience

**Software Testing Intern · EGEMSOFT / Türk Telekom**<br>
<sub>Performance testing with JMeter, Oracle database testing, found critical deployment issues, built a data mining demo in Python.</sub>

**Software Intern · Kazancı Holding**<br>
<sub>Multi-layer .NET architecture, MS SQL Server integration, Docker deployment.</sub>

**Istanbul Ticaret University**<br>
<sub>Ranked 1st in the faculty, GPA 3.54 / 4.00.</sub>

<details>
<summary><b>Earlier projects</b></summary>
<br>

- [Vehicle image classification](https://github.com/emrtunali/vehicle-image-classification-transfer-learning): transfer learning with EfficientNet
- [Fish species classifier](https://github.com/emrtunali/Deep-Learning-Fish-AI): a CNN tuned with Keras Tuner
- [Android chat app](https://github.com/emrtunali/ChatApp): real-time messaging with Firebase authentication (Java)
- [Client-server chat](https://github.com/emrtunali/Server-Client-Chat): secure messaging on Windows (C#, .NET)
- [Cargo tracking system](https://github.com/emrtunali/Cargo-Tracking-Sysytem) and a [logistics website](https://github.com/emrtunali/Lojistik_Web_Sitesi)
- iOS apps: [machine learning on iOS](https://github.com/emrtunali/Ios-Machine-Learning), [brain training](https://github.com/emrtunali/Brain-Trainin-App)

</details>
