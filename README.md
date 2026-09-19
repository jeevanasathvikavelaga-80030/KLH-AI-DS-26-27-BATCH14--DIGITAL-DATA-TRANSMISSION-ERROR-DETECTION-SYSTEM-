# KLH-<AI-DS>-<26-27>-<BATCH14>--<DIGITAL-DATA-TRANSMISSION-ERROR-DETECTION-SYSTEM>

# Design and Simulation of a Digital Data Transmission Error Detection System

## Team Members

| Name | Registration Number |
|---|---|
| Jeevana Sathvika Velaga | 2620080030 |
| Saraswathi Venkata Sripathi Raju | 2620080059 |
| Pachipalu Manishashanth | 2620080068 |
| Kadapala Abhinav | 2620080076 |

## Supervisor

**Dr. Kartheek V.**

---

## Project Abstract

The **Digital Data Transmission Error Detection System** is designed to detect errors that may occur while transmitting digital data from a sender to a receiver.

During digital data transmission, bits may get changed or corrupted due to noise, interference, or other transmission problems. The system uses digital logic and error detection techniques to determine whether the received data is correct or contains an error.

This project demonstrates the basic principles of digital data communication and shows how digital logic circuits can be used to improve the reliability of data transmission.

The system consists of a data input section, error detection logic, a simulated transmission channel, an error injection mechanism, a receiver, and an error indication output.

---

## Project Objectives

The main objectives of this project are:

- To understand the basic principles of digital data transmission.
- To understand how errors can occur during digital communication.
- To design a digital logic-based error detection system.
- To simulate the transmission of digital data from a sender to a receiver.
- To introduce and simulate transmission errors.
- To detect whether the received data contains an error.
- To verify the system using different test cases.
- To document the design, implementation, simulation, and results.

---

## System Overview

The proposed system follows the basic digital data transmission process:

**Sender → Error Detection/Encoding → Transmission Channel → Receiver → Error Checking → Output**

The sender generates digital data and adds the required error detection information. The data is then transmitted through a simulated communication channel.

An error can be introduced during transmission to represent data corruption. The receiver checks the received data using the error detection logic and produces an output indicating whether an error has been detected.

---

## System Block Diagram

```text
             DIGITAL DATA
                  |
                  v
        +--------------------+
        |      SENDER        |
        |   Data Generator   |
        +---------+----------+
                  |
                  v
        +--------------------+
        | Error Detection    |
        |     Generator      |
        +---------+----------+
                  |
                  v
        +--------------------+
        | Transmission       |
        |      Channel       |
        +---------+----------+
                  |
           Possible Error
                  |
                  v
        +--------------------+
        |      RECEIVER      |
        |   Data Reception   |
        +---------+----------+
                  |
                  v
        +--------------------+
        | Error Detection    |
        |      Checker       |
        +---------+----------+
                  |
                  v
        +--------------------+
        |  Error Indicator   |
        +--------------------+
             |          |
             v          v
        NO ERROR    ERROR DETECTED
