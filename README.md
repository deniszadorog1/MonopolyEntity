# MonopolyEntity

A Monopoly game built with C# and WPF as a learning project — inspired by [monopoly-one.com](https://monopoly-one.com/).

![Gameplay](Visuals/GameProcess.png)

## Features

**Gameplay**
- Classic Monopoly mechanics with real-world brand properties (Nike, Apple, Pepsi, Audi, Facebook and more)
- Buy, upgrade and mortgage businesses
- Pay rent when landing on opponent's property
- Star-based upgrade system (up to 4 stars + hotel)
- Game log showing all events in real time

**Cases & Inventory**
- Open cases with keys to receive random properties
- Inventory system — browse owned items with search and rarity filters
- Cases can drop bonus stations that increase rent income

**Business Card**
- Detailed property card: base rent, rent per upgrade level, buy/deposit/rebuy prices

**Players**
- Player avatars and balance displayed on the sidebar
- Skull icon for eliminated players

## Screenshots

![Business Card](Visuals/BusinessCard.png)
![Inventory](Visuals/Inventory.png)
![Case Opening](Visuals/Case.png)

> Add your screenshots to the `Images/` folder to display them here.

## Stack

- **C# / WPF** — desktop UI
- **Entity Framework** — data persistence (Database First)
- **Material Design in XAML** — UI components

## Getting Started

1. Clone the repo and open `MonopolyEntity.sln` in Visual Studio
2. Restore NuGet packages
3. Hit F5

## Project Structure

```
MonopolyDLL/        # game logic, models, EF DbContext
MonopolyEntity/     # WPF views and viewmodels
```
