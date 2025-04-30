# Tuni'Art

**Tuni'Art** is a comprehensive, multi-platform web application curated by local Tunisian artists, aimed at both Tunisians and non-Tunisians. It serves as a digital space where users can discover artists, browse artworks, explore events, and participate in live auctions. All user and content data is synced across platforms, including a connected Java-based application.

## Features

- 🎨 **Artist Directory**: Explore a list of registered artists on the homepage.
- 🖼️ **Art Gallery**: Browse art pieces uploaded by local creators.
- 📅 **Event Listings**: View upcoming art events and exhibitions.
- 🏷️ **Auctions**: Participate in or follow live and upcoming auctions.
- 🔄 **Cross-Platform Sync**: Signing up or uploading on one platform updates data on the other (Symfony app ↔ Java app).

## Tech Stack

- **Symfony Framework** (PHP)
- **Twig** for templating
- **CSS** for design
- **JavaScript** for dynamic events
- **Yaml** 
- **MySQL** (via XAMPP) 

## Getting Started

Follow these steps to set up and run the project locally:

### Prerequisites

- [XAMPP](https://www.apachefriends.org/index.html) (Apache & MySQL)
- [Symfony CLI](https://symfony.com/download)
- PHP >= 8.1

### Installation

1. **Start XAMPP**  
   Launch XAMPP and ensure both **Apache** and **MySQL** services are running.

2. **Extract Files**  
   Extract the project folder into `htdocs` (usually located in `C:/xampp/htdocs`).

3. **Start Symfony Server**  
   Open a terminal in the project directory and run:

   ```bash
   symfony serve

4. **Access the Homepage**
   Open your navigator and add /home to the localhost url provided (i.e http://127.0.0.1:8000/home)
