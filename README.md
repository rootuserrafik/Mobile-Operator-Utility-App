# App Summary  
**An All-in-One Operator Dashboard to Simplify Your Mobile Experience**

---

## 📌 Core Concept

This application serves as a centralized, user-friendly hub for managing all essential mobile operator services.  
The primary goal is to replace complex USSD codes and confusing SMS commands with a clean, intuitive graphical interface, allowing users to perform actions like checking balances, activating offers, and sending service requests with a single tap.

---

## ⭐ Key Features & Pages

| Feature            | Icon       | Description                                                                 |
|--------------------|------------|-----------------------------------------------------------------------------|
| **🏠 Home Dashboard**  | `home`      | The app's entry point, displaying operator info and quick access to core functions. |
| **📦 Offers & Details** | `local_offer` | A browsable catalog of data, minute, and combo packs, with a detail view for each offer. |
| **📲 Dial Codes**      | `dialpad`   | A categorized, searchable library of important USSD codes like *#06# or *121#. |
| **📤 SMS Services**    | `sms`       | A guided interface to send pre-formatted SMS requests (e.g., NID check). |
| **🧾 History Log**     | `history`   | A filterable log of user actions like sent SMS, activated offers, etc.     |
| **⚙️ Settings & Help** | `settings`  | Lets users configure app preferences and access help/contact/legal info.   |

---

## 🎨 Design & UX Philosophy

- 🔷 **Clean & Consistent UI**  
  Uses a consistent "Operator Classic" color palette (Blue, White, Gray) and modern typography (Poppins + Roboto).

- 🎯 **Action-Oriented Design**  
  Every screen centers around a clear CTA (Call-To-Action). Buttons are large, accessible, and provide tactile feedback.

- 🧩 **Structured Layouts**  
  Uses cards, grids, and visual hierarchy to make info scannable and reduce cognitive load.

- ✅ **User Control & Feedback**  
  Real-time feedback for actions (e.g., toasts, state changes). Users control language, SIM, and theme settings.

---

## 🧭 Common User Flow Example

1. **Launch the app** to the Home Dashboard showing SIM & Operator info.
2. Tap **"View Offers"** → Navigate to the Offers Page → Filter by **Internet**.
3. Tap on a pack → See **Offer Details Page** (price, validity, etc.).
4. Hit **"Activate Now"** → Success confirmation appears.  
   The action is logged in the **History Log**.

---

## 🔡 Fonts Used

- **Poppins**: For headings and key labels  
- **Roboto**: For body text and input labels

---

## 🎨 Color Variables (Operator Classic Theme)

| Use Case             | Color       | Hex Code   |
|----------------------|-------------|------------|
| Primary Accent       | Blue        | `#0077C2`  |
| Background           | Light Gray  | `#F4F6F8`  |
| Card Background      | White       | `#FFFFFF`  |
| Primary Text         | Black       | `#212121`  |
| Secondary Text       | Gray        | `#424242`  |
| Divider              | Light Gray  | `#E0E0E0`  |
| Button Text          | White       | `#FFFFFF`  |
| Success Text         | Green       | `#2E7D32`  |
| Error Text           | Red         | `#D32F2F`  |

---

## ✅ Design Tokens Summary

- **Button Radius**: `12px`
- **Card Radius**: `16px`
- **Input Border**: `#CCCCCC`
- **Shadow**: `0 4px 12px rgba(0, 0, 0, 0.08)`

---

Let me know if you want this as a downloadable `.md` file or turned into a GitHub README or Notion-style documentation!
