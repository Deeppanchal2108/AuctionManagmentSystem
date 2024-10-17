# Auction Management System

The Auction Management System is a Java console-based application that facilitates online auctions. It implements advanced concepts like thread synchronization and data structures to ensure efficient and reliable auction operations. The system is backed by SQL for data storage, providing a robust platform for managing auctions in real-time.

## Features

- **User Authentication**: Allows users to register and log in to participate in auctions.
- **Auction Creation**: Registered users can create auctions by specifying item details, starting bids, and auction duration.
- **Real-time Bidding**: Supports concurrent real-time bidding, ensuring fair and safe access using thread synchronization.
- **Bid History**: Users can track and view the bidding history of auctions, adding transparency.
- **Admin Panel**: Administrators can manage users, auctions, and monitor activities in real-time.

## Technologies Used

- **Java**: Core language used for developing the application.
- **Thread Synchronization**: Ensures data consistency and manages concurrent access to shared resources during bidding.
- **Data Structures**: Used for efficient storage and management of user data, auction details, and bid history.
- **SQL**: For data storage and efficient querying of auction data.

## Prerequisites

To run this application, you'll need the following software installed on your system:

- **Java Development Kit (JDK)**: [Download JDK](https://www.oracle.com/java/technologies/javase-downloads.html)

## Getting Started

Follow these instructions to get the Auction Management System up and running on your local machine.

### Installation

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/Deeppanchal2108/AuctionManagmentSystem.git
    cd AuctionManagmentSystem
    ```

2. **Compile and Run the Java Application**:
    - Compile the Java project using any IDE or the command line:
      ```bash
      javac AuctionSystem.java
      java AuctionSystem
      ```

### How to Use

- **Register and Login**: Start by registering as a user. Once registered, log in to create and participate in auctions.
- **Create an Auction**: Users can create auctions by providing details like the item name, starting bid, and auction duration.
- **Place Bids**: While an auction is active, multiple users can place bids. The system will handle concurrent bidding using thread synchronization.
- **View Bid History**: Users can view a detailed bid history for each auction, keeping track of all the bids.
- **Admin Panel**: Administrators can log in to monitor and manage auctions and users.

## Contributions

Feel free to fork this repository and submit pull requests. Any contributions that enhance the system or fix issues are welcome.


