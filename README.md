# up2d8: Canvas File Synchronization

## Introduction

up2d8 is a work-in-progress Java project that simplifies the process of synchronizing files from your Canvas account to a specified folder on your personal device. With up2d8, you can effortlessly keep your Canvas files up-to-date on your local machine.

## Features

- **Synchronize Canvas Files**: Automatically fetch and update files from your Canvas account.
- **Customizable Folder**: Choose the destination folder on your device for file synchronization.
- **Easy to Use**: A user-friendly interface for hassle-free setup and management.

## Getting Started

Follow these steps to get started with up2d8:

1. Clone this repository to your local machine.


2. Configure your Canvas API credentials in the `config.json` file.

```json
{
  "canvas_api_key": "your_canvas_api_key_here",
  "canvas_api_url": "https://your_canvas_domain.instructure.com/api/v1/"
}

```
3. Customize the synchronization settings in the `up2d8.json` file.
   ```json
   {
   "canvas_folder_id": 123456, // Your Canvas folder ID
   "local_folder_path": "/path/to/your/local/folder"
   }

4. Compile and run up2d8 to begin the synchronization process.

## Contributions
Contributions to up2d8 are welcome! Feel free to fork this repository, make improvements, and submit pull requests to enhance the project.

## License
This project is licensed under the MIT License.
