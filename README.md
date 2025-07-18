# Pristine - Fashion Auction Website

Pristine is a sophisticated, full-stack web application that brings the thrill of real-time auctions to the world of high-end fashion. It provides a dynamic and engaging platform for users to discover, bid on, and win exclusive clothing items for men, women, and children. The application is meticulously crafted with a modern technology stack, ensuring a seamless, secure, and performant user experience.

---

## 🌟 About The Project

In the fast-paced world of fashion, Pristine offers a unique and exciting way for enthusiasts to acquire coveted pieces. Our platform is designed to solve the problem of limited access to exclusive fashion items by creating a transparent and competitive marketplace. Whether you're a seasoned collector or a fashion-forward individual, Pristine provides an elegant and intuitive interface to participate in thrilling auctions from the comfort of your home.

### Key Features

* **🔐 Secure User Authentication**: Powered by **Clerk**, our authentication system ensures a safe and reliable experience. Users can easily sign up, log in, and manage their profiles with robust security measures in place.

* **🛍️ Curated Product Categories**: To enhance the user's shopping experience, our platform is organized into three main categories: **Men**, **Women**, and **Children**. This allows for easy navigation and discovery of items tailored to specific interests.

* **🔨 Diverse Auction Types**: Pristine offers two distinct auction formats to cater to different bidding strategies:
    * **Standard Auction**: The classic auction model where the highest bidder wins the item.
    * **Sealed Auction**: A unique format where bids are hidden, and the highest unique bid wins, adding an element of strategy and suspense.

* **⏱️ Real-Time Bidding**: Experience the excitement of a live auction with our real-time bidding system. Bids are updated instantly, allowing users to stay engaged and make timely decisions.

* **👑 Automatic Winner Assignment**: Our intelligent system automatically processes the results of each auction as it concludes. The winner is determined based on the auction type and notified promptly, ensuring a fair and efficient process.

* **🖥️ Comprehensive Admin Dashboard**: A powerful and intuitive dashboard provides administrators with full control over the platform. Admins can effortlessly **create**, **edit**, and **delete** product listings, as well as monitor all bidding activity to ensure the integrity of the auctions.

---

## 🛠️ Technologies Used

Pristine is built with a selection of cutting-edge technologies to deliver a modern and responsive web application.

* ### Frontend
    * **[Next.js](https://nextjs.org/)**: A React framework for building fast and scalable web applications.
    * **[React](https://reactjs.org/)**: A JavaScript library for building user interfaces.
    * **[Tailwind CSS](https://tailwindcss.com/)**: A utility-first CSS framework for rapid UI development.
    * **[Framer Motion](https://www.framer.com/motion/)**: A production-ready motion library for React, used to create fluid animations and engaging user interactions.

* ### Backend
    * **[Next.js API Routes](https://nextjs.org/docs/api-routes/introduction)**: Serverless functions for building the backend logic.
    * **[Prisma](https://www.prisma.io/)**: A next-generation ORM that simplifies database access and management.
    * **[MongoDB](https://www.mongodb.com/)**: A flexible and scalable NoSQL database used to store all application data.

* ### Authentication
    * **[Clerk](https://clerk.dev/)**: A complete user management solution that handles authentication, user profiles, and session management.

---

## 🚀 Getting Started

To set up a local instance of Pristine, please follow the instructions below.

### Prerequisites

Make sure you have the following software installed on your machine:

* **Node.js**: Version 18.17.0 or higher.
* **Package Manager**: `npm`, `yarn`, or `pnpm`.

### Installation

1.  **Clone the Repository**
    ```sh
    git clone [https://github.com/harenimuthu/pristine.git](https://github.com/harenimuthu/pristine.git)
    ```

2.  **Navigate to the Project Directory**
    ```sh
    cd pristine
    ```

3.  **Install Dependencies**
    ```sh
    npm install
    ```

4.  **Set Up Environment Variables**

    Create a `.env` file in the root of the project and add the following environment variables. You will need to obtain these keys from their respective services.

    ```env
    # MongoDB Connection String
    DATABASE_URL="your_mongodb_connection_string"

    # Clerk API Keys
    NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY="your_clerk_publishable_key"
    CLERK_SECRET_KEY="your_clerk_secret_key"
    ```

5.  **Run the Development Server**
    ```sh
    npm run dev
    ```

6.  **View the Application**

    Open your browser and navigate to [http://localhost:3000](http://localhost:3000) to see the application in action.

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

## 📝 License

Distributed under the MIT License. See `LICENSE` for more information.
