# GuardianID Africa Empowering African Health Sovereignty through MOSIP-integrated AI Diagnostics.

GuardianID is a "Personal Health Guardian" designed for the Africa Digital ID Hackathon 2026. It bridges the gap between foundational identity (MOSIP) and actionable, high-value healthcare.

## The Vision
In many African regions, healthcare is reactive and fragmented. GuardianID transforms the Digital ID from a passive card into an active life-saving tool. By storing medical records as Verifiable Credentials and using on-device AI, we predict health risks before they become emergencies—even without an internet connection.

## Technical Stack
* Identity: [MOSIP](https://mosip.io) (eSignet & Inji Wallet)
* AI Engine: TensorFlow Lite (Edge AI for offline prediction)
* Data Standard: W3C Verifiable Credentials (VCs)
* Frontend: React Native (Mobile-first)
* Privacy: Zero-Knowledge Proofs (ZKP) for selective disclosure

## Architecture
1. Root of Trust: User authenticates via MOSIP.
2. Credential Issuance: Health ministries issue signed health records to the Inji-based wallet.
3. Local Intelligence: The 'Anya' AI agent analyzes data locally to provide preventative alerts.
4. Sovereign Sharing: Patients share only necessary proofs with clinicians using ZKPs.

## Impact Goals
- Reduce Maternal Mortality: Early AI detection of pregnancy risks.
- Lower System Costs: Eliminate redundant testing through data portability.
- Inclusion: Offline-first design for rural and displaced populations.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.