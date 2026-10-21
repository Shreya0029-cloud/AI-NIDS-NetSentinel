\# 🛡️ NetSentinel AI Pro



\### AI-Powered Network Intrusion Detection \& Security Intelligence Platform



> 🚀 Live Demo: https://netsentinel-ai-pro-yp0k.onrender.com/



> 🔗 GitHub: https://github.com/Shreya0029-cloud/AI-NIDS-NetSentinel



NetSentinel AI Pro is an end-to-end \*\*AI-powered Network Intrusion Detection System (NIDS)\*\* engineered to transform raw network traffic into actionable security intelligence.



The platform combines \*\*packet and PCAP analysis, network-flow generation, feature engineering, rule-based security detection, machine-learning-based anomaly detection, attack classification, threat scoring, incident generation, and interactive security visualization\*\* into a unified cybersecurity platform.



Instead of simply displaying packets, NetSentinel processes network behavior through a complete detection pipeline designed to answer three critical questions:



> \*\*What happened? Why is it suspicious? How severe is the threat?\*\*



\---



\# 🚀 Project Highlights



| Capability | Implementation |

|---|---|

| 📦 PCAP Analysis | Scapy-based packet parsing |

| 🌐 Flow Analysis | Source-destination flow generation |

| 🧬 Feature Engineering | 9 network \& TCP traffic features |

| 🤖 ML Detection | Random Forest + Isolation Forest |

| 🛡️ Security Detection | Hybrid rule + ML pipeline |

| 🚨 Attack Detection | SYN Flood, DoS patterns, Port Scanning |

| 📊 Threat Intelligence | Threat scoring \& severity classification |

| 🔔 Incident Processing | Detection → Incident → Alert |

| 🖥️ Dashboard | Interactive security visualization |

| 🌐 Networking Lab | OSI, IPv4, Dijkstra, TCP concepts |

| 🐳 Deployment | Docker + Render |

| 🧪 Testing | Automated Python tests |



\---



\# 🧠 Why NetSentinel?



Traditional packet analyzers expose large volumes of low-level network information, while signature-based intrusion detection systems can struggle with previously unseen or abnormal behavior.



\*\*NetSentinel uses a hybrid approach.\*\*



```text

&#x20;                NETWORK TRAFFIC

&#x20;                       │

&#x20;                       ▼

&#x20;               ┌───────────────┐

&#x20;               │ Packet / PCAP │

&#x20;               │    Input      │

&#x20;               └───────┬───────┘

&#x20;                       │

&#x20;                       ▼

&#x20;               ┌───────────────┐

&#x20;               │ Scapy Packet  │

&#x20;               │    Parsing    │

&#x20;               └───────┬───────┘

&#x20;                       │

&#x20;                       ▼

&#x20;               ┌───────────────┐

&#x20;               │ Flow Generation│

&#x20;               └───────┬───────┘

&#x20;                       │

&#x20;                       ▼

&#x20;               ┌───────────────┐

&#x20;               │    Feature    │

&#x20;               │   Extraction  │

&#x20;               └───────┬───────┘

&#x20;                       │

&#x20;            ┌──────────┴──────────┐

&#x20;            │                     │

&#x20;            ▼                     ▼

&#x20;    ┌───────────────┐     ┌───────────────┐

&#x20;    │ Rule-Based    │     │ Machine       │

&#x20;    │ Detection     │     │ Learning      │

&#x20;    └───────┬───────┘     └───────┬───────┘

&#x20;            │                     │

&#x20;            └──────────┬──────────┘

&#x20;                       ▼

&#x20;               ┌───────────────┐

&#x20;               │ Hybrid Threat │

&#x20;               │   Detection   │

&#x20;               └───────┬───────┘

&#x20;                       │

&#x20;                       ▼

&#x20;               ┌───────────────┐

&#x20;               │ Attack        │

&#x20;               │ Classification│

&#x20;               └───────┬───────┘

&#x20;                       │

&#x20;                       ▼

&#x20;               ┌───────────────┐

&#x20;               │ Threat Score  │

&#x20;               │ \& Severity    │

&#x20;               └───────┬───────┘

&#x20;                       │

&#x20;                       ▼

&#x20;               ┌───────────────┐

&#x20;               │   Incident    │

&#x20;               │   Generation  │

&#x20;               └───────┬───────┘

&#x20;                       │

&#x20;                       ▼

&#x20;               ┌───────────────┐

&#x20;               │ Security      │

&#x20;               │ Dashboard     │

&#x20;               └───────────────┘

```



\---



\# 🔥 Core Features



\## 📦 1. Intelligent PCAP Analysis



NetSentinel accepts network capture files and automatically converts raw packet data into structured security information.



The analysis pipeline performs:



\- Packet parsing

\- Protocol inspection

\- Source/destination extraction

\- Flow generation

\- TCP flag analysis

\- Traffic statistics

\- Feature extraction

\- Suspicious behavior detection

\- Attack classification

\- Threat scoring

\- Security incident generation



This enables analysts to move from \*\*raw packet captures → meaningful security insights\*\*.



\---



\# 🌐 2. Network Flow Generation



Rather than analyzing packets independently, NetSentinel groups related traffic into communication flows.



A flow represents communication between network endpoints and provides a more meaningful representation of network behavior.



```text

Source IP

&#x20;   │

&#x20;   ├── Source Port

&#x20;   │

&#x20;   ▼

Network Flow

&#x20;   │

&#x20;   ├── Destination IP

&#x20;   ├── Destination Port

&#x20;   ├── Protocol

&#x20;   ├── Packet Count

&#x20;   ├── Byte Count

&#x20;   └── TCP Flags

```



This flow-based representation provides the foundation for feature engineering and machine-learning analysis.



\---



\# 🧬 3. Network Feature Engineering



NetSentinel extracts \*\*nine security-relevant features\*\* from network flows.



| Feature | Purpose |

|---|---|

| Packet Count | Measures traffic volume |

| Byte Count | Measures transferred data |

| Duration | Measures flow lifetime |

| Packets/sec | Measures packet transmission intensity |

| Bytes/sec | Measures bandwidth intensity |

| SYN Count | Identifies connection initiation behavior |

| ACK Count | Identifies acknowledged traffic |

| RST Count | Detects connection resets |

| FIN Count | Detects connection termination |



These features transform raw network traffic into structured numerical representations suitable for machine-learning and rule-based detection.



\---



\# 🤖 4. Machine Learning Detection



NetSentinel integrates two complementary machine-learning approaches.



\### 🌲 Random Forest



Used for supervised classification of network traffic based on extracted traffic characteristics.



\### 🌳 Isolation Forest



Used for anomaly detection by identifying network flows that behave differently from normal traffic patterns.



The combination allows the system to approach intrusion detection from both:



```text

Known Attack Classification

&#x20;           +

Unknown / Abnormal Behavior Detection

```



\---



\# 🛡️ 5. Hybrid Detection Engine



One of the core architectural features of NetSentinel is its \*\*hybrid detection pipeline\*\*.



Instead of relying exclusively on machine learning, the system combines:



```text

┌─────────────────────────┐

│   Rule-Based Detection  │

│                         │

│ Known security patterns │

└────────────┬────────────┘

&#x20;            │

&#x20;            │

&#x20;            ▼

&#x20;     ┌─────────────┐

&#x20;     │    Hybrid   │

&#x20;     │  Detection  │

&#x20;     │    Engine   │

&#x20;     └─────────────┘

&#x20;            ▲

&#x20;            │

&#x20;            │

┌────────────┴────────────┐

│   Machine Learning      │

│                         │

│ Classification +        │

│ Anomaly Detection       │

└─────────────────────────┘

```



This architecture combines deterministic security logic with statistical and machine-learning analysis.



\---



\# 🚨 6. Attack Detection



NetSentinel is designed to identify suspicious behaviors including:



\### SYN Flood



Large volumes of SYN traffic can indicate an attempt to exhaust connection resources.



\### Denial-of-Service Patterns



Abnormal traffic rates and flow characteristics can indicate potential DoS activity.



\### Port Scanning



Repeated connection attempts across ports can indicate reconnaissance activity.



\### Suspicious TCP Behavior



TCP flag distributions and unusual traffic characteristics can be used as indicators of suspicious behavior.



\---



\# 📊 7. Threat Scoring



Detected network events are assigned a threat score to help prioritize incidents.



Example:



```text

┌─────────────────────────────────────┐

│          SECURITY INCIDENT          │

├─────────────────────────────────────┤

│ Attack       : SYN Flood            │

│ Source       : 10.0.0.10            │

│ Destination  : 10.0.0.20            │

│ Threat Score : 92                    │

│ Severity     : CRITICAL              │

└─────────────────────────────────────┘

```



Threat scoring provides a simple way to distinguish between lower-risk anomalies and high-priority security events.



\---



\# 🔔 8. Incident \& Alert Pipeline



NetSentinel converts detections into structured security incidents.



```text

Detection

&#x20;   ↓

Threat Evaluation

&#x20;   ↓

Threat Score

&#x20;   ↓

Severity Classification

&#x20;   ↓

Incident Creation

&#x20;   ↓

Alert

&#x20;   ↓

Dashboard Visualization

```



This provides a foundation for extending the platform toward SIEM-style security monitoring.



\---



\# 🖥️ 9. Security Dashboard



The frontend provides an interactive security-oriented interface for exploring analysis results.



The dashboard can display:



\- Total flows analyzed

\- Detection count

\- Critical incidents

\- Threat scores

\- Attack categories

\- Source IP

\- Destination IP

\- Traffic statistics

\- PCAP analysis results

\- Security reports

\- Detection insights



Example:



```text

╔══════════════════════════════════════╗

║       NETSENTINEL AI PRO             ║

╠══════════════════════════════════════╣

║                                      ║

║  FLOWS       DETECTIONS     CRITICAL ║

║   100            98             2    ║

║                                      ║

╠══════════════════════════════════════╣

║                                      ║

║  SYN FLOOD                           ║

║  10.0.0.10 → 10.0.0.20              ║

║  Threat Score: 92                    ║

║  Severity: CRITICAL                  ║

║                                      ║

╚══════════════════════════════════════╝

```



\---



\# 🌐 10. Computer Networks Engineering Lab



NetSentinel also includes a dedicated networking learning module.



Topics include:



\### OSI Model



Understanding the seven layers of computer networking.



\### Network Protocols



Exploring how protocols enable communication across networks.



\### IPv4 Subnetting



Working with network addresses, subnet masks, hosts, and CIDR concepts.



\### Dijkstra's Algorithm



Demonstrating shortest-path routing concepts.



\### TCP Congestion Control



Exploring how TCP manages network congestion.



\### Network Performance



Analyzing traffic behavior and network performance characteristics.



This connects the practical NIDS implementation with fundamental \*\*Computer Networks engineering concepts\*\*.



\---



\# 🏗️ System Architecture



```text

&#x20;                       ┌─────────────────────┐

&#x20;                       │       USER          │

&#x20;                       └──────────┬──────────┘

&#x20;                                  │

&#x20;                                  ▼

&#x20;                       ┌─────────────────────┐

&#x20;                       │   Web Dashboard     │

&#x20;                       │ HTML / CSS / JS     │

&#x20;                       └──────────┬──────────┘

&#x20;                                  │

&#x20;                                  ▼

&#x20;                       ┌─────────────────────┐

&#x20;                       │     FastAPI         │

&#x20;                       │    Backend API      │

&#x20;                       └──────────┬──────────┘

&#x20;                                  │

&#x20;                ┌─────────────────┼─────────────────┐

&#x20;                │                 │                 │

&#x20;                ▼                 ▼                 ▼

&#x20;       ┌──────────────┐   ┌──────────────┐   ┌──────────────┐

&#x20;       │    Scapy     │   │     ML       │   │   Security   │

&#x20;       │ Packet Engine│   │   Pipeline   │   │    Engine    │

&#x20;       └──────┬───────┘   └──────┬───────┘   └──────┬───────┘

&#x20;              │                  │                  │

&#x20;              └──────────────────┼──────────────────┘

&#x20;                                 ▼

&#x20;                        ┌─────────────────┐

&#x20;                        │ Threat Analysis │

&#x20;                        └────────┬────────┘

&#x20;                                 │

&#x20;                                 ▼

&#x20;                        ┌─────────────────┐

&#x20;                        │    Incidents    │

&#x20;                        │   \& Reports     │

&#x20;                        └─────────────────┘

```



\---



\# 🔄 Complete Detection Lifecycle



```text

Raw Network Traffic

&#x20;       │

&#x20;       ▼

&#x20;    PCAP File

&#x20;       │

&#x20;       ▼

&#x20; Packet Parsing

&#x20;       │

&#x20;       ▼

&#x20;Flow Generation

&#x20;       │

&#x20;       ▼

Feature Extraction

&#x20;       │

&#x20;       ├───────────────┐

&#x20;       ▼               ▼

&#x20;Rule Engine      ML Models

&#x20;       │               │

&#x20;       │       ┌───────┴────────┐

&#x20;       │       │                │

&#x20;       │       ▼                ▼

&#x20;       │ Random Forest   Isolation Forest

&#x20;       │       │                │

&#x20;       └───────┴────────────────┘

&#x20;                   │

&#x20;                   ▼

&#x20;         Hybrid Detection

&#x20;                   │

&#x20;                   ▼

&#x20;         Attack Classification

&#x20;                   │

&#x20;                   ▼

&#x20;            Threat Score

&#x20;                   │

&#x20;                   ▼

&#x20;             Severity

&#x20;                   │

&#x20;                   ▼

&#x20;              Incident

&#x20;                   │

&#x20;                   ▼

&#x20;                Alert

&#x20;                   │

&#x20;                   ▼

&#x20;            Dashboard

```



\---



\# 🧪 Example Detection Scenario



Consider a network capture containing a large number of TCP SYN packets.



NetSentinel analyzes the traffic and extracts:



```text

Packet Count

SYN Count

ACK Count

RST Count

FIN Count

Packets/sec

Bytes/sec

Duration

Byte Count

```



Suppose the system observes:



```text

Very high SYN rate

\+

Low ACK response

\+

Abnormal packets/sec

\+

Unusual flow behavior

```



The detection pipeline evaluates the flow using both security rules and ML models.



The result can be:



```text

Attack Type : SYN Flood

Threat Score: 92

Severity    : CRITICAL

```



The event is then converted into a security incident and displayed on the dashboard.



\---



\# 🧰 Technology Stack



\## Backend



\- Python

\- FastAPI

\- Scapy

\- REST APIs



\## Machine Learning



\- Scikit-learn

\- Random Forest

\- Isolation Forest

\- Feature Engineering

\- Anomaly Detection

\- Classification



\## Frontend



\- HTML5

\- CSS3

\- JavaScript

\- Interactive Dashboard



\## Networking



\- TCP/IP

\- PCAP

\- Network Flows

\- TCP Flags

\- IPv4

\- Subnetting

\- Network Algorithms



\## Cybersecurity



\- Network Intrusion Detection

\- Threat Detection

\- Attack Classification

\- Threat Scoring

\- Incident Generation

\- Security Analytics



\## DevOps



\- Git

\- GitHub

\- Docker

\- Docker Compose

\- Render



\---



\# 📁 Project Structure



```text

AI-NIDS-NetSentinel/

│

├── app/

│   ├── main.py

│   ├── models.py

│   ├── network.py

│   ├── ml.py

│   ├── database.py

│   ├── reports.py

│   └── cn\_lab.py

│

├── frontend/

│   ├── index.html

│   ├── app.js

│   └── styles.css

│

├── models/

│

├── reports/

│

├── scripts/

│   └── generate\_demo\_pcap.py

│

├── tests/

│   └── test\_core.py

│

├── uploads/

│   └── demo\_syn\_flood.pcap

│

├── Dockerfile

├── docker-compose.yml

├── render.yaml

├── requirements.txt

├── .env.example

├── .gitignore

└── README.md

```



\---



\# 🐳 Docker Deployment



NetSentinel supports containerized deployment.



Build and start the application using:



```bash

docker compose up --build

```



Docker provides a reproducible environment for running the application across development and deployment environments.



\---



\# 💻 Local Development



\## 1. Clone Repository



```bash

git clone https://github.com/Shreya0029-cloud/AI-NIDS-NetSentinel.git

cd AI-NIDS-NetSentinel

```



\## 2. Create Virtual Environment



```bash

python -m venv .venv

```



\### Windows



```bash

.venv\\Scripts\\activate

```



\### Linux / macOS



```bash

source .venv/bin/activate

```



\## 3. Install Dependencies



```bash

pip install -r requirements.txt

```



\## 4. Configure Environment



Create a `.env` file based on:



```text

.env.example

```



\*\*Never commit API keys, passwords, credentials, or other secrets.\*\*



\## 5. Start the Application



```bash

uvicorn app.main:app --reload

```



\---



\# 🧪 Testing



Run the test suite using:



```bash

pytest

```



The project includes automated tests for core application functionality.



\---



\# ☁️ Cloud Deployment



NetSentinel AI Pro is configured for deployment using \*\*Render\*\*.



Deployment configuration is provided through:



```text

Dockerfile

docker-compose.yml

render.yaml

```



\### 🌐 Production Demo



🚀 \*\*Live Application:\*\*



https://netsentinel-ai-pro-yp0k.onrender.com/



\---



\# 🔐 Security \& Responsible Use



NetSentinel is intended for:



\- Defensive cybersecurity research

\- Network security education

\- Authorized network monitoring

\- Controlled security testing

\- Academic projects

\- Cybersecurity experimentation



Only analyze traffic and systems that you own or have explicit authorization to inspect.



Do not use the platform for unauthorized monitoring, disruption, exploitation, or attacks against third-party systems.



\---



\# 🎯 Engineering Objectives



The project demonstrates the integration of multiple engineering disciplines:



```text

Computer Networks

&#x20;      +

Cybersecurity

&#x20;      +

Machine Learning

&#x20;      +

Backend Engineering

&#x20;      +

Frontend Engineering

&#x20;      +

Data Processing

&#x20;      +

DevOps

&#x20;      ↓

NetSentinel AI Pro

```



The objective was not simply to build a machine-learning classifier.



The objective was to build an \*\*end-to-end cybersecurity system\*\* capable of taking network traffic as input and converting it into meaningful security intelligence.



\---



\# 📈 Future Roadmap



Potential future enhancements include:



\- ⚡ Real-time packet capture

\- 🧠 Deep-learning intrusion detection

\- 🔬 LSTM / Transformer-based traffic modeling

\- 🌍 GeoIP-based attack visualization

\- 🔗 SIEM integration

\- 📡 Threat-intelligence integration

\- 📧 Email security alerts

\- 💬 Slack/Teams notifications

\- 🧠 Explainable AI for predictions

\- 🔄 Continuous ML model retraining

\- ☸️ Kubernetes deployment

\- 📊 Advanced security analytics

\- 🔐 Role-based security administration

\- 🌐 Distributed network monitoring



\---



\# 💡 Key Engineering Concepts Demonstrated



NetSentinel demonstrates practical knowledge of:



\- Network packet processing

\- PCAP analysis

\- Network flow generation

\- Feature engineering

\- TCP/IP networking

\- TCP flag analysis

\- Rule-based intrusion detection

\- Supervised machine learning

\- Unsupervised anomaly detection

\- Random Forest classification

\- Isolation Forest anomaly detection

\- Threat scoring

\- Security incident processing

\- REST API development

\- Full-stack application architecture

\- Docker containerization

\- Cloud deployment

\- Automated testing

\- Git/GitHub workflows



\---



\# ⭐ Why This Project Matters



NetSentinel demonstrates how multiple technologies can work together to solve a real-world cybersecurity problem.



The platform follows a complete engineering lifecycle:



```text

&#x20;                   RAW DATA

&#x20;                      │

&#x20;                      ▼

&#x20;              NETWORK ANALYSIS

&#x20;                      │

&#x20;                      ▼

&#x20;             FEATURE ENGINEERING

&#x20;                      │

&#x20;                      ▼

&#x20;            MACHINE LEARNING

&#x20;                      │

&#x20;                      ▼

&#x20;            THREAT DETECTION

&#x20;                      │

&#x20;                      ▼

&#x20;           ATTACK CLASSIFICATION

&#x20;                      │

&#x20;                      ▼

&#x20;             THREAT SCORING

&#x20;                      │

&#x20;                      ▼

&#x20;            SECURITY INCIDENT

&#x20;                      │

&#x20;                      ▼

&#x20;             VISUAL ANALYTICS

&#x20;                      │

&#x20;                      ▼

&#x20;               CLOUD DEPLOYMENT

```



This makes NetSentinel a practical demonstration of \*\*AI engineering, cybersecurity, computer networking, full-stack development, and cloud deployment working together in one production-oriented project.\*\*



\---



\# 🏆 Project Summary



> \*\*NetSentinel AI Pro is an AI-powered Network Intrusion Detection and Security Intelligence Platform that transforms raw network traffic and PCAP captures into actionable security insights through packet analysis, flow-based feature engineering, hybrid rule-based and machine-learning detection, attack classification, threat scoring, incident generation, and interactive visualization.\*\*



\---



\## 🚀 Explore NetSentinel



\### 🌐 Live Demo

https://netsentinel-ai-pro-yp0k.onrender.com/



\### 💻 GitHub Repository

https://github.com/Shreya0029-cloud/AI-NIDS-NetSentinel



\---



\### 🛡️ NetSentinel AI Pro



\*\*Detect. Analyze. Classify. Respond.\*\*



\*Turning network traffic into security intelligence.\*

