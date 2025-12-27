
# ResolveX: Smart Grievance Resolution Platform

[![Next.js](https://img.shields.io/badge/Next.js-15.x-black?style=for-the-badge&logo=next.js)](https://nextjs.org/)
[![Firebase](https://img.shields.io/badge/Firebase-v10-orange?style=for-the-badge&logo=firebase)](https://firebase.google.com/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-v3-blue?style=for-the-badge&logo=tailwind-css)](https://tailwindcss.com/)
[![License](https://img.shields.io/badge/License-MIT-purple?style=for-the-badge)](./LICENSE)

ResolveX is an all-in-one platform for reporting, tracking, and resolving civic issues. It connects citizens directly with local authorities, using real-time data and AI-driven insights to build safer, more responsive communities.

---

## 🏆 GOOGLE H25 Hack Ananta Hackathon

This project was proudly developed by **Panda Gang** for the GOOGLE H25 Hack Ananta hackathon.

### Team Members
-   **Rohan Das** (Team Leader) - `2420080057`
-   **Sai Praneetha Oruganty** - `2420080061`
-   **M Nikhileshwar Reddy** - `2420080064`
-   **Amrutha Reddy** - `2420080079`

---

## ✨ Key Features

### For Citizens
-   **🚀 Instant Reporting:** Submit grievances like potholes or broken streetlights in seconds with a geo-tagged photo.
-   **🗺️ Live Map Tracking:** View all reported issues on an interactive map, and track the status of your reports in real-time.
-   **🧭 Smart Navigation:** Get turn-by-turn directions that actively route you around known hazards for a safer journey.

### For Administrators
-   **📊 Command Center:** Get a bird's-eye view of all grievances with a live map and a risk-based heatmap to identify hotspots instantly.
-   **📈 Advanced Analytics:** Analyze grievance trends by status, category, and submission dates to uncover systemic issues.
-   **🤖 AI-Powered Insights:** Leverage an AI Impact Simulator to forecast how resolving issues will reduce future complaints and overall risk.

---

## 🛠️ Technology Stack

ResolveX is built with a modern, scalable, and powerful technology stack to deliver a seamless experience.

| Technology | Description |
| :--- | :--- |
| **Next.js & React** | For a high-performance, server-rendered user interface. |
| **Firebase** | Provides the backend-as-a-service for real-time data, authentication, and storage. |
| **Google Maps Platform** | Powers our core features, including live maps, heatmaps, and smart route navigation. |
| **Genkit & Gemini** | Drives our AI features, including description enhancement and risk analysis. |
| **Tailwind CSS & ShadCN/UI** | For rapid, utility-first styling that creates a modern and responsive design system. |
| **Vercel / Firebase App Hosting** | For seamless, continuous deployment and global hosting. |

---

## 🚀 Getting Started

Follow these steps to get a local copy of ResolveX up and running.

### Prerequisites

-   [Node.js](https://nodejs.org/) (v18 or higher)
-   [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)

### Installation & Setup

1.  **Clone the repository:**
    ```sh
    git clone https://github.com/your-username/resolvex.git
    cd resolvex
    ```

2.  **Install dependencies:**
    ```sh
    npm install
    ```

3.  **Set up environment variables:**
    Create a file named `.env.local` in the root of your project and add your Google Maps API key:
    ```env
    NEXT_PUBLIC_GOOGLE_MAPS_API_KEY=YOUR_GOOGLE_MAPS_API_KEY
    NEXT_PUBLIC_GOOGLE_MAPS_MAP_ID=YOUR_MAP_ID
    ```

4.  **Run the development server:**
    ```sh
    npm run dev
    ```

The application should now be running on [http://localhost:9002](http://localhost:9002).

---

## 📂 Project Structure

```
/
├── src/
│   ├── app/                # Next.js App Router: pages, layouts
│   ├── components/         # Reusable React components (UI, layout, etc.)
│   ├── lib/                # Shared utilities, types, and constants
│   ├── firebase/           # Firebase configuration and custom hooks
│   └── ai/                 # Genkit flows for AI functionality
├── public/                 # Static assets
└── README.md
```

---

## 🤝 Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".

1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the Branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

---

## 📜 License

Distributed under the MIT License. See `LICENSE` for more information.
