# System Architecture

### 1. Identity Layer (MOSIP)
We utilize the Modular Open Source Identity Platform (MOSIP) as our foundational identity layer.
- eSignet: Used for OIDC-compliant authentication.
- Inji Wallet: The primary interface for storing Decentralized Identifiers (DIDs).

### 2. Intelligence Layer (Edge AI)
To solve the connectivity issue in rural Africa, we use TensorFlow Lite.
- The model is trained on global health datasets and fine-tuned for regional African health markers.
- Privacy: No raw health data is sent to the cloud. The "Compute-to-Data" model ensures all analysis happens on the handset.

### 3. Verification Layer
Using Zero-Knowledge Proofs (ZKP), a patient can prove a "Health Status" (e.g., "Cleared for Work" or "Vaccination Complete") without revealing their underlying medical history or ID numbers.