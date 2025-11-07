Here’s a clean, ready-to-copy **README.md** for your web-based tool for **Tasha Properties**.
If you want this stored in a canvas for future edits, just tell me.

---

# **Tasha Properties – Web-Based Tool**

A lightweight, browser-based tool designed to streamline daily property management tasks for **Tasha Properties Pty Ltd**. This tool centralizes operations, improves efficiency, and ensures consistent workflows for the team.

---

## **✅ Features**

* **Booking & Client Management**
  Track guest details, booking information, invoices, and property assignments.

* **Automated Invoice Generation**
  Generates Beds24-ready invoice HTML templates with custom branding.

* **Property Information Dashboard**
  Displays key property details, cleaning schedules, guest notes, and operational checklists.

* **File & Media Handling**
  Supports cloud-hosted images (e.g., OneDrive links) for invoice logos and documents.

* **Responsive Web Design**
  Fully accessible on desktop, tablet, and mobile.

---

## **📁 Project Structure**

```
/root
 ├── index.html          # Main interface
 ├── /assets
 │     ├── styles.css    # Styles and layout
 │     ├── script.js     # Application logic
 │     └── logo.png      # Tasha Properties logo
 ├── /templates
 │     └── invoice.html  # Beds24 invoice template
 └── README.md           # Project documentation
```

---

## **🛠 Installation & Setup**

This tool is fully web-based. No server setup required.

### **Option 1 — Local Use**

1. Download all project files.
2. Open `index.html` in any browser (Chrome recommended).
3. Start using the tool immediately.

### **Option 2 — Cloud Hosting**

You can host the tool on:

* Google Drive (public HTML hosting)
* Netlify
* GitHub Pages
* Any web server

Just upload the full folder and ensure paths remain intact.

---

## **⚙ Configuration**

### **Invoice Logo**

To change the logo for invoice templates:

1. Replace `/assets/logo.png`
   **or**
2. Update the HTML to use a direct image URL (public OneDrive or other CDN).

### **Beds24 Integration**

* Ensure template variables (e.g., `[BOOKID]`, `[GUESTNAME]`, `[ROOM]`) remain intact.
* Paste the HTML output from `/templates/invoice.html` directly into your Beds24 invoice template.

---

## **📖 Usage**

1. Open the tool from your browser.
2. Navigate using the top menu:

   * **Properties**
   * **Invoices**
   * **Bookings**
   * **Resources**
3. Enter or paste data where needed (e.g., invoice numbers, guest details).
4. Export or copy generated HTML directly into Beds24.

---

## **🔧 Customization**

You may update:

* Colors and branding via `styles.css`
* Logic or automation in `script.js`
* Invoice layout inside `/templates/invoice.html`
