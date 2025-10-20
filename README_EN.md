# Public Use Cases Collection

## Project Introduction

This project contains a collection of practical use cases that demonstrate the core functionality of the system, covering various application scenarios from basic queries to advanced automated workflows. Each use case provides detailed documentation in both Chinese and English to help users quickly understand and master the system's usage methods.

## Use Cases Overview

### 📊 Basic Query Cases

#### 1. Stock Price Query
- **File Location**: [chn/stock-price-query.md](chn/stock-price-query.md) | [eng/stock-price-query.md](eng/stock-price-query.md)
- **Description**: Demonstrates the system's default browser tool functionality, supporting both Simple mode and Plan-Act enhanced mode
- **Key Features**: 
  - Simple chat interface query
  - Variable parameter query for different company stock prices
  - Detailed execution process display
- **Use Cases**: Financial information query, stock price monitoring

#### 2. IP Query
- **File Location**: [chn/ip-query.md](chn/ip-query.md) | [eng/ip-query.md](eng/ip-query.md)
- **Description**: Demonstrates MCP service integration methods to extend system functionality through external services
- **Key Features**:
  - MCP service configuration and management
  - SSE connection method
  - External service invocation
- **Use Cases**: Network information query, IP location services

### 🔧 Advanced Feature Cases

#### 3. Form Input Demo
- **File Location**: [chn/form-input-demo.md](chn/form-input-demo.md) | [eng/form-input-demo.md](eng/form-input-demo.md)
- **Description**: Demonstrates user interaction waiting mechanisms and login state persistence functionality
- **Key Features**:
  - Form-input tool usage
  - Asynchronous user interaction handling
  - Browser session state maintenance
- **Use Cases**: Website operations requiring user login, interactive workflows

#### 4. Query Plan
- **File Location**: [chn/query-plan.md](chn/query-plan.md) | [eng/query-plan.md](eng/query-plan.md)
- **Description**: Demonstrates DeepResearch-type application implementation, embodying the "functions as first-class citizens" design philosophy and function-agent capabilities. Achieves intelligent deep research search functionality by decomposing complex tasks into reusable tool functions
- **Key Features**:
  - Function-agent capabilities: Intelligent function composition and automatic task decomposition
  - Function composition and reuse: Support for decomposing complex tasks into reusable tool functions
  - Complex task decomposition: Automatic identification and splitting of research tasks
  - Answer generation based on real data: All answers are based on actual content from accessed pages
  - Clear citation and evidence presentation: Provides complete citation chains and evidence support
  - Intelligent research strategy: Automatic selection of optimal research paths and resources
- **Use Cases**: Deep research, academic research, information gathering, intelligent analysis

#### 5. Image and PDF Recognition
- **File Location**: [chn/image-pdf-recognition.md](chn/image-pdf-recognition.md) | [eng/image-pdf-recognition.md](eng/image-pdf-recognition.md)
- **Description**: Demonstrates image and PDF recognition functionality, supporting batch recognition and structured output, as well as HTTP API calls
- **Key Features**:
  - Document parsing and OCR technology
  - Structured data extraction
  - HTTP service publishing and calling
  - File upload and batch processing
  - Asynchronous task execution
  - JSON format standardized output
- **Use Cases**: Document processing, content extraction, batch recognition, API services

#### 6. AI Novel
- **File Location**: [chn/ai-novel.md](chn/ai-novel.md) | [eng/ai-novel.md](eng/ai-novel.md)
- **Description**: Demonstrates integrated output of long-form content and function-agent implementation, completing long-form content creation through divide-and-conquer strategy, supporting batch production of long articles
- **Key Features**:
  - Integrated long-form content output: Breaking through context limitations to achieve coherent long-form content generation
  - Function-agent implementation: Intelligent task decomposition and tool function composition, embodying "functions as first-class citizens" philosophy
  - Batch production of long articles: Supporting chapter-based writing workflow, reusable for long-form content creation on different topics
  - Divide-and-conquer strategy: Decomposing complex creation tasks into manageable chapter units
  - Content coherence assurance: Ensuring logical consistency and style uniformity between chapters
- **Use Cases**: Content creation, creative writing, batch article production, long-form document generation

## Technical Architecture

### Core Components
- **Plan-Act Mode**: The system's main working mode, supporting complex task planning and execution
- **Tool Integration**: Built-in browser_use tools and external MCP service integration
- **Function Composition**: Support for decomposing complex tasks into reusable tool functions
- **State Management**: Support for browser session and login state persistence

### Supported Features
- ✅ Simple query mode
- ✅ Enhanced plan execution
- ✅ Variable parameter support
- ✅ External service integration
- ✅ User interaction waiting
- ✅ Function publication and reuse
- ✅ Deep research search

## Quick Start

1. **Select Use Case**: Choose the appropriate use case documentation based on your needs
2. **Read Instructions**: Carefully read the Chinese and English documentation
3. **Follow Steps**: Execute operations according to the steps in the documentation
4. **View Results**: Observe the system execution process and results

## File Structure

```
public-usecase/
├── README.md                    # Project overview (Chinese)
├── README_EN.md                # Project overview (English)
├── chn/                        # Chinese version use case docs
│   ├── stock-price-query.md    # Stock Price Query
│   ├── ip-query.md            # IP Query
│   ├── form-input-demo.md     # Form Input Demo
│   ├── query-plan.md          # Query Plan
│   ├── image-pdf-recognition.md # Image and PDF Recognition
│   └── ai-novel.md           # AI Novel
└── eng/                       # English version use case docs
    ├── stock-price-query.md   # Stock Price Query
    ├── ip-query.md           # IP Query
    ├── form-input-demo.md    # Form Input Demo
    ├── query-plan.md         # Query Plan
    ├── image-pdf-recognition.md # Image and PDF Recognition
    └── ai-novel.md          # AI Novel
```

## Contributing

Contributions of new use cases and improvements to existing documentation are welcome. Please ensure:
- Provide both Chinese and English versions
- Use clear step numbering
- Include expected results and technical points
- Maintain consistent documentation formatting

## License

This project uses an open source license. Please see the LICENSE file for specific information.

## Discussion

Click this link to join the DingTalk group for discussion: [dingtalk group](https://qr.dingtalk.com/action/joingroup?code=v1,k1,PBuFX00snERuKcnnG4YAPK52FOXwAkLYlulUUD9KiRo=&_dt_no_comment=1&origin=11)
