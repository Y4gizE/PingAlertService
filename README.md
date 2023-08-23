# PingAlertService

PingAlertService is a Java application developed to monitor the reachability of specified IP addresses and send email alerts in case of unavailability.

## Description

PingAlertService is a monitoring tool that periodically checks the reachability of multiple IP addresses. It uses the Java programming language and libraries such as javax.mail and java.net to perform its tasks. The tool logs the results in a text file and sends email notifications if any of the monitored servers become unreachable.

## Requirements

- Java Development Kit (JDK) 20
- Internet connectivity for email alerts

## Installation

1. Clone or download this repository.
2. Open the project in your preferred Java development environment (e.g., Apache NetBeans 18).
3. Update the IP addresses and email settings in the `WindowsService.java` file.
4. Compile and run the `WindowsService.java` file.

## Usage

1. Run the compiled Java application (`WindowsService` class) to start monitoring the specified IP addresses.
2. The application will periodically ping the specified IP addresses and log the results in a text file.
3. If a server becomes unreachable, the application will send email alerts to the specified recipients.

## Configuration

Open the `WindowsService.java` file and update the following settings:

- Set the `fileLocation` variable to the desired location for the log file.
- Update the `ipAddress` array with the IP addresses you want to monitor.
- Set the `recipients` array to the email addresses that should receive alerts.
- Configure the `fromEmail` and `mailHost` variables for email notifications.

## Contributing

Contributions to this project are welcome! If you would like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them with descriptive messages.
4. Push your changes to your fork.
5. Create a pull request detailing your changes.

