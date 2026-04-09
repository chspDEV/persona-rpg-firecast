# PersonaRPG Plugin (Firecast)

> A plugin developed for the Firecast app, featuring a custom and automated character sheet for the Persona RPG system.

This plugin is based on the **Grimoire of Heart** system rules, specifically adapted to allow players and Game Masters to manage character sheets directly within Firecast using Lua scripting and the native LFM (Lua Form Macros) visual interface.

-----

## Main Concept

The goal of this project is to streamline the gameplay experience for Persona RPG campaigns. It automates attribute calculations, inventory management, and Persona tracking, following the structure provided by the [Grimoire of Heart](https://github.com/grimoireofheart/grimoireofheart.github.io/tree/main/PT) system.

## Features

  * **Multi-tab Character Sheet:** Organized sections for Attributes, Personas, Inventory, and Notes.
  * **Automatic Calculations:** Derived stats and weight limits updated in real-time.
  * **Persona Management:** Dedicated space for multiple Personas, including their specific skills, resistances, and weaknesses.
  * **Custom Visual Interface:** Designed using the Firecast SDK 3, incorporating custom images and native UI components.

-----

## Technologies Used

  * **Language:** Lua
  * **Interface:** LFM (Lua Form Macros)
  * **Framework:** Firecast SDK 3

-----

## How to Install and Use

**Prerequisites:**

  * [Firecast](https://firecast.app/) installed.
  * Basic knowledge of how to import `.rpk` files.

**Step by Step:**

1.  Download the `PersonaFicha.rpk` file from the `output` folder.
2.  Double-click the file or drag it into the Firecast window.
3.  Create a new character in your table and select the "Ficha Persona Editavel" template.

## Repository Structure

  * `/FichaPersonaEditavel`: Contains the source `.lfm` files for the interface.
  * `/images`: Visual assets used in the character sheet.
  * `/output`: Contains the compiled `.rpk` plugin ready for use.
  * `/sdk`: Support scripts and Firecast libraries.

-----

## License

This project is licensed under the MIT License.
