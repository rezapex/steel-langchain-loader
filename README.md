# Steel Langchain Document Loader

## Overview

This package provides a document loader for Langchain that integrates with Steel.dev's web automation capabilities.

## Installation

```bash
pip install steel-langchain-loader
```

## Usage

```python
from steel_langchain_loader import SteelLoader

# Create a loader
loader = SteelLoader(
    url='https://example.com',
    steel_config={
        'host': 'steel.dev',  # or your self-hosted Steel instance
        'api_key': 'your_steel_api_key'
    }
)

# Load documents
documents = loader.load()
```

## Features
- Support for Steel Cloud and Self-hosted Steel
- Comprehensive error handling
- Flexible configuration
