# Fair Calculator

A simple web application to calculate per-item food prices after applying a proportional discount with a maximum cap, similar to food delivery app vouchers.

FairShare Calc is a minimalist, single-page web application designed to help users proportionally distribute a total discount across a list of food items. Users input a discount percentage and a maximum discount value, then list their food items with price and quantity. The application instantly calculates the total gross price, determines the actual discount applied (respecting the cap), and then allocates this discount proportionally to each item based on its contribution to the total cost.

## Key Features

-   **Proportional Discount Calculation**: Fairly distributes a total discount across multiple items based on their value.
-   **Flexible Discount Rules**: Supports percentage-based discounts with a configurable maximum cap.
-   **Dynamic Item List**: Easily add or remove food items to the calculation list.
-   **Real-Time Updates**: All calculations update instantly as you type, providing immediate feedback.
-   **Detailed Breakdown**: View the original price, discount applied, and final price for each individual item.
-   **Clear Summary**: Get a clean overview of the total cost before discount, total savings, and the final amount payable.
-   **Responsive Design**: A clean, modern, and fully responsive interface that works beautifully on any device.

## Technology Stack

-   **Framework**: React (Vite)
-   **Language**: TypeScript
-   **Styling**: Tailwind CSS with shadcn/ui components
-   **State Management**: Zustand
-   **Animations**: Framer Motion
-   **Icons**: Lucide React
-   **Deployment**: Cloudflare Workers

## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

-   [NodeJS](https://nodejs.org/) installed on your machine.
-   [Git](https://git-scm.com/) for cloning the repository.

### Installation

1.  **Clone the repository:**
    ```sh
    git clone https://github.com/your-username/fairshare-calc.git
    cd fairshare-calc
    ```

2.  **Install dependencies:**
    The project uses npm for package management.
    ```sh
    npm install
    ```

3.  **Run the development server:**
    This command starts the Vite development server.
    ```sh
    npm run dev
    ```
    The application will be available at `http://localhost:3000`.


## License

This project is licensed under the MIT License.