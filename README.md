# 🚀 Dynamic Document Upload Interface

This interface is a **parameter-driven web application**. It uses **URL Query Parameters** to build the UI on the fly, allowing you to change the title, badge, and required file list without editing the code.

## 🛠 How to Use (URL Construction)

To customize the page, append specific keys and values to your URL starting with a `?`. Use `&` to separate different parameters.

### Base URL
`http://127.0.0.1:5500/dynamicFileUpload.html`

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
[http://127.0.0.1:5500/dynamicFileUpload.html?title=DMS%20Document%20Upload&files=DMS%20Registration%20Invoice,FORUM%2022,FORM%2023&badge=DevOps%20Upload%20Pipeline&banner=DMS%20Invoice%20Completed&bannerMsg=Files%20are%20being%20uploaded]
(http://127.0.0.1:5500/dynamicFileUpload.html?title=RTO%20Document%20Upload&files=DMS%20Registration%20Invoice,FORUM%2022,FORUM123,HElloworld&badge=Deva%20Upload%20Pipeline&banner=DMS%20Invoice%20Completed&bannerMsg=Files%20are%20being%20uploaded)...
