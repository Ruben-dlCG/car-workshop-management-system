# Architectural Overview

This file blueprints the architectural foundation of the project. Its goal is to show the structural patterns that dictate how data flows from end to end, with a explicit focus on the different layers that shape the application schema, and the tools used to that effect. 

Note that, at this stage of development, two distinct phases have been planned. Consequently, the underlying architecture varies in some key aspects from phase 1 to phase 2.

## 📊 Interactive Model
The architectural structure is periodically maintained and subjected to be updated in Lucidchart, so as to ensure accurate representation of data models, processing boundaries and tool selection for each phase of the project.

👉 [Launch Interactive Architectural Diagram on Lucidchart](https://lucid.app/lucidchart/6a210dec-8a84-4b0c-881a-b9db306e6c1c/edit?viewport_loc=-322%2C-442%2C3380%2C1419%2CKJ1d39JUXv3b&invitationId=inv_65ed33ba-0e84-44a3-8c7d-8cff54ffcd8e)

## 🔑 Key Strategic Patterns Applied
- **Defined Project Phases:** Due to time limitations and current technical skill gaps, the lifecycle of this project has been split into two defined phases, each holding their own characteristics and supporting different functions. For additional details on this, please refer to the `README.md` file available [here](https://github.com/Ruben-dlCG/car-workshop-management-system/blob/main/README.md)
- **Layered Architecture:** The central piece of how this whole project is meant to be built lies upon the division of data in distinct layers of information. Each layer helps define the scope of the processed data at that specific point in the system. For example, a class named `InventoryService` is meant to be part of the Service Layer, as its only purpose is to handle core business logistics and coordinating data persistence.
- **Separation of Concerns:** Each layer and module is strictly responsible for one set of specific tasks, which helps on keeping a clean and highly maintainable system.
