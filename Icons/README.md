# Azure Service Icon Metadata Generator

This tool generates rich metadata about Azure services based on their icon files.

## How It Works

The script:
1. Reads the icon-data.json file containing all Azure service icons
2. Uses the Ollama API to generate descriptive information for each service
3. Creates a single consolidated service-info.json file in the root directory
4. Tracks progress and can be resumed if interrupted

## Generated Information

For each Azure service icon, the script generates:

## Prerequisites

1. Node.js installed
2. Ollama installed locally (https://ollama.ai)
3. A language model pulled into Ollama (e.g., `ollama pull mistral`)

## Installation

1. Navigate to the scripts directory
2. Run `npm install` to install dependencies

## Usage

1. Make sure Ollama is running locally
2. Run the generator:

