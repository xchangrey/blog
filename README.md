# Project Overview

Welcome to the project! This repository contains the implementation of our latest project. 

## Using ngrok for Backend

To serve JSON for the backend, we use ngrok to expose the local server to the internet. The backend code is located in a separate repository: [jsonserver](https://github.com/xchangrey/jsonserver).

### Steps to Use ngrok

1. Clone the [jsonserver](https://github.com/xchangrey/jsonserver) repository.
2. Navigate to the jsonserver directory.
3. Install the necessary dependencies.
4. Start the JSON server.
5. Download and install ngrok from [ngrok.com](https://ngrok.com/).
6. Run the following command to expose the JSON server:

    ```sh
    ngrok http 3000
    ```

    Replace `3000` with the port number your JSON server is running on.

7. ngrok will provide a public URL that you can use to access the JSON server from the internet.

By following these steps, you can easily serve JSON for the backend using ngrok.

## Subdirectory

Please note that a subdirectory within this project contains the upgraded React Navigation v6 implementation of the same project. This upgrade brings several improvements and new features to enhance the navigation experience in our application.

Feel free to explore the subdirectory to see the updated implementation and understand the changes made.

## Getting Started

To get started with this project, follow the instructions below:

1. Clone the repository.
2. Navigate to the project directory.
3. Install the necessary dependencies.
4. Run the project.

We hope you find this project useful and informative. If you have any questions or feedback, please feel free to reach out.

Happy coding!