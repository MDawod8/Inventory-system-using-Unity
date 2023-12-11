# Unity Inventory System

This Unity project provides a basic inventory system that allows players to manage items, combine them, and perform various inventory-related actions. The system is designed to be flexible and easily integrated into Unity projects.

## Features

- **Item Management:** Add, remove, and list items in the inventory.
- **Combining Items:** Combine specific items to create new ones based on predefined combinations.
- **Equip and Discard Items:** Equip and discard items from the inventory.
- **UI Integration:** Simple Unity UI elements to interact with the inventory.

## Getting Started

### Prerequisites

- Unity 3.5.1 or later

### Installation

1. Clone the repository:

2. Import the project in Unity.

3. Run the project in the Unity Editor to see the inventory system in action.

## Usage

### InventoryManager Script

The core functionality of the inventory system is managed by the `InventoryManager` script. This script includes methods for adding, removing, and combining items, as well as UI interactions.

#### Combine Items

To combine items, follow these steps:

1. Select the first item by clicking on its corresponding UI button.
2. Press the "Combine" button.
3. Select the second item.
4. The combination logic will be executed based on predefined rules.

### Item Script

The `Item` scriptable object defines the properties of each item in the inventory. You can customize item types, such as weapons, ammo, herbs, and more, by editing this script.

### UI Integration

Buttons in the Unity UI are used to interact with the inventory system. Attach the `UIController` script to each button to handle item selection.
