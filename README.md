<h1 align="center">Hi, I'm Touseef 👋</h1>

<p align="center">
I build networks as code: real routing protocols in containerlab, proven by tests before anything changes,<br>
deployed by pipelines and watched by live dashboards. I also build AI and full stack apps.
</p>

<p align="center">
<a href="https://www.touseefahmed.com"><img src="https://img.shields.io/badge/Website-www.touseefahmed.com-1D4FA0?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Website: www.touseefahmed.com"></a>
<img src="https://img.shields.io/badge/Based%20in-Milan%2C%20Italy-2B7A4A?style=for-the-badge" alt="Based in: Milan, Italy">
</p>

<hr>

<ul>
  <li>IT support engineer at Nokia in Milan, for enterprise users across Italy, France and Switzerland</li>
  <li>MSc in AI for Science and Technology, University of Milano-Bicocca</li>
  <li>Freelance AI and full stack developer</li>
  <li>Every lab below runs on my own server, with a public status page you can open right now</li>
</ul>

<h2>Running live</h2>

<table>
<tr>
<td width="50%" valign="top">
<h3><a href="https://github.com/ahmed-touseef/evpn-fabric-cicd">EVPN fabric CI/CD</a></h3>
<p>A data center fabric (EVPN, VXLAN, eBGP unnumbered) that only changes through a pipeline: intent in YAML, Batfish proofs, 58 tests on a booted copy, then a pull based deploy agent with canary and rollback. Every night it breaks itself on purpose: a frozen spine is dropped in under 0.6 s.</p>
<p><b>Live:</b> <a href="https://cicd.touseefahmed.com">cicd.touseefahmed.com</a></p>

</td>
<td width="50%" valign="top">
<h3><a href="https://github.com/ahmed-touseef/mini-isp">Mini ISP</a></h3>
<p>A 15 router service provider: IS-IS with Segment Routing and BFD, BGP with route reflectors, two transits and an internet exchange, CGNAT, anycast DNS and a real home over WireGuard. NetBox is the source of truth. BFD cut silent failure detection from 28.9 s to 0.34 s.</p>
<p><b>Live:</b> <a href="https://noc.touseefahmed.com">noc.touseefahmed.com</a></p>

</td>
</tr>
<tr>
<td width="50%" valign="top">
<h3><a href="https://github.com/ahmed-touseef/italy-wan-lab">Italy WAN lab</a></h3>
<p>Six cities joined in an OSPF ring, rebuilt from a Packet Tracer design into containerlab, with 24 office sites and WireGuard remote access into Milan. The map shows the path traffic takes right now.</p>
<p><b>Live:</b> <a href="https://wan.touseefahmed.com">wan.touseefahmed.com</a></p>

</td>
<td width="50%" valign="top">
<h3><a href="https://github.com/ahmed-touseef/e-commerce">Eurofiora e-commerce</a></h3>
<p>A demo flower shop for a Milan business: shop, vendor and admin portals served by one FastAPI service, routed by hostname, on PostgreSQL with Alembic migrations.</p>
<p><b>Live:</b> <a href="https://shop.eurofiora.it">shop.eurofiora.it</a></p>

</td>
</tr>
<tr>
<td colspan="2" valign="top">
<h3><a href="https://github.com/ahmed-touseef/neurotablet-assistant">NeuroTablet Assistant</a></h3>
<p>A domain restricted AI chatbot for cognitive health topics. RAG over FAISS with Sentence Transformers, LLaMA 3.3 70B through Groq, layered defenses against prompt injection, isolated sessions and audit logs.</p>

</td>
</tr>
</table>

<h2>Tech stack</h2>

<h4>Networking</h4>
<p>
<img src="https://img.shields.io/badge/BGP-1D4FA0?style=for-the-badge" alt="BGP">
<img src="https://img.shields.io/badge/EVPN%20VXLAN-1D4FA0?style=for-the-badge" alt="EVPN VXLAN">
<img src="https://img.shields.io/badge/IS--IS-1D4FA0?style=for-the-badge" alt="IS-IS">
<img src="https://img.shields.io/badge/OSPF-1D4FA0?style=for-the-badge" alt="OSPF">
<img src="https://img.shields.io/badge/Segment%20Routing-1D4FA0?style=for-the-badge" alt="Segment Routing">
<img src="https://img.shields.io/badge/MPLS-1D4FA0?style=for-the-badge" alt="MPLS">
<img src="https://img.shields.io/badge/BFD-1D4FA0?style=for-the-badge" alt="BFD">
<img src="https://img.shields.io/badge/CGNAT-1D4FA0?style=for-the-badge" alt="CGNAT">
<img src="https://img.shields.io/badge/WireGuard-88171A?style=for-the-badge&logo=wireguard&logoColor=white" alt="WireGuard">
<img src="https://img.shields.io/badge/FRRouting-2B3A47?style=for-the-badge" alt="FRRouting">
<img src="https://img.shields.io/badge/containerlab-2B3A47?style=for-the-badge" alt="containerlab">
<img src="https://img.shields.io/badge/Batfish-2B3A47?style=for-the-badge" alt="Batfish">
<img src="https://img.shields.io/badge/NetBox-2B3A47?style=for-the-badge" alt="NetBox">
</p>

<h4>Languages</h4>
<p>
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
<img src="https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white" alt="Bash">
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
<img src="https://img.shields.io/badge/SQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="SQL">
</p>

<h4>Backend and web</h4>
<p>
<img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI">
<img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React">
<img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js">
<img src="https://img.shields.io/badge/Node.js-5FA04E?style=for-the-badge&logo=nodedotjs&logoColor=white" alt="Node.js">
<img src="https://img.shields.io/badge/Jinja-7E0C1B?style=for-the-badge&logo=jinja&logoColor=white" alt="Jinja">
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL">
</p>

<h4>AI</h4>
<p>
<img src="https://img.shields.io/badge/RAG-6D28D9?style=for-the-badge" alt="RAG">
<img src="https://img.shields.io/badge/FAISS-0467DF?style=for-the-badge&logo=meta&logoColor=white" alt="FAISS">
<img src="https://img.shields.io/badge/Sentence%20Transformers-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" alt="Sentence Transformers">
<img src="https://img.shields.io/badge/LLaMA-0467DF?style=for-the-badge&logo=meta&logoColor=white" alt="LLaMA">
</p>

<h4>Infrastructure and DevOps</h4>
<p>
<img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux">
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker">
<img src="https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white" alt="Nginx">
<img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" alt="GitHub Actions">
<img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white" alt="Prometheus">
<img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white" alt="Grafana">
<img src="https://img.shields.io/badge/Let%27s%20Encrypt-003A70?style=for-the-badge&logo=letsencrypt&logoColor=white" alt="Let's Encrypt">
<img src="https://img.shields.io/badge/Hetzner-D50C2D?style=for-the-badge&logo=hetzner&logoColor=white" alt="Hetzner">
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git">
</p>
