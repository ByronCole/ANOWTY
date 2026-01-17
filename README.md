# ANOWTY
Welcome to the ANOWTY app where we say the common since advice no one will tell you.

The app's true power lies in its ability to reconcile different accounting methods (W2 vs. 1099) while maintaining a high-fidelity audit trail that a legal defender can use to challenge SSA overpayment claims.

### 1. The Reconciliation Engine (Utility)

The primary utility is catching discrepancies between your recorded work (W2 effort) and what your employer reports to the SSA (1099/Paystub cash).

* **W2 Logic:** Tracks hours when they were actually worked, which is the legal standard for SSDI.
* **1099 Logic:** Tracks when the money hit your bank, which is often how the SSA incorrectly audits.
* **Variance Detection:** If your employer's reported pay exceeds your calculated work by more than **5%**, the app triggers a critical alert, allowing you to investigate immediately rather than waiting for an SSA letter months later.

### 2. The Multi-Fork Strategy (Optionality)

To ensure this tool remains useful for other benefit types (like SSI, VA benefits, or specialized legal defense), the architecture uses a **Modular Route Tree**:

* **Configurable Thresholds:** Organizations can "fork" the settings to change the Substantial Gainful Activity (SGA) limit ($1,690) or the Trial Work Period (TWP) threshold ($1,210) to match different state or federal programs.
* **Defense Toggles:** Legal defenders can enable "Hard Audit Mode," which forces users to upload images for every entry, creating a verifiable chain of custody for evidence.
* **Custom Motivation Engine:** The coaching messages can be swapped from SSDI-specific advice to general vocational rehabilitation support.

### 3. "Safe Work" Dashboard

The dashboard provides a "Safe Hours" readout, translating complex dollar limits into actionable time. This allows users to work with confidence, knowing exactly how many hours remain before they hit a critical threshold.

| Feature | Exploring Mode | Defense Mode (Forked) |
| **Cushioning** | 5% (Conservative) | 0-1% (Precision) |
| **Logging** | Disposable/Editable | Immutable/Timestamped |
| **Evidence** | Optional | Mandatory for Export |

### 4. SSA-Ready Exporting

The ultimate utility is the **Audit Report**. With one tap, the app generates a PDF containing:

* A 13-month earnings summary.
* Verification of all 245+ daily work entries.
* Attached images of every paystub used for reconciliation.
* Technical explanations for any detected variances.

This report is designed to "speak" the SSA's language, potentially ending an audit before it begins by providing more complete records than the employer or the bank.
