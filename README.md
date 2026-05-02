# 🚀 Dynamic Document Upload Interface

This interface is a **parameter-driven web application**. It uses **URL Query Parameters** to build the UI on the fly, allowing you to change the title, badge, and required file list without editing the code.

## 🛠 How to Use (URL Construction)

To customize the page, append specific keys and values  to your URL starting with a `?`. Use `&` to separate different parameters.

### Base URL
`https://belladcompany.github.io/Devops-File-Upload.html`

### Available Parameters

| Parameter | Description | Requirement | Example |
| :--- | :--- | :--- | :--- |
| `title` | The main heading displayed at the top of the card. | **Required** | `title=RTO Document Upload` |
| `files` | A comma-separated list of files needed. | **Required** | `files=Invoice,Form 22,ID Proof` |
| `badge` | A small pill label above the title. | Optional | `badge=DevOps Pipeline` |
| `banner` | Title for the green notification box. | Optional | `banner=Upload Started` |
| `bannerMsg` | Detailed text for the notification box. | Optional | `bannerMsg=Processing...` |

---

## 🔗 Copy-Paste Example URL

You can copy the link below and replace the values to test your configuration:

```text
[https://belladcompany.github.io/Devops-File-Upload/?title=DMS%20Document%20Upload%20&files=GST%20Registration%20Invoice,Form%2022&badge=DevOps%20Upload%20Pipeline%20&banner=DMS%20Invoice%20Completed%20&bannerMsg=Files%20are%20being%20uploaded...]
(https://belladcompany.github.io/Devops-File-Upload/?title=DMS%20Document%20Upload%20&files=GST%20Registration%20Invoice,Form%2022&badge=DevOps%20Upload%20Pipeline%20&banner=DMS%20Invoice%20Completed%20&bannerMsg=Files%20are%20being%20uploaded...)...
