# Tao360: Revolutionizing How We Evaluate Subnets

**Authors:** [Sam Pierre](https://x.com/notYourBananaa) and [Ben-Zion Benkhin](https://x.com/benzion_b)

*Dec. 11, 2024*

*Download Blog [PDF](https://drive.google.com/file/d/1ldkypVg_7Yu9RHKWR8Zui7KMuANrBbmo/view?usp=drive_link)*

*Download Full Report [PDF](https://drive.google.com/file/d/1bFU_3rIBFaHF817b29KjPhwN3z_I1NtB/view?usp=drive_link)*

In Bittensor's growing ecosystem of AI subnets, determining fair emissions allocations and measuring subnet performance remains a critical challenge. Tao360 offers a promising solution: an AI-powered subnet data aggregator that analyzes network metrics to provide valuation insights. This innovative proof-of-concept system represents the first step toward data-driven emissions allocation. The following dives into the current analysis approach and recent network-wide results, and opens the discussion for future development.

**Important Note:** The findings presented here demonstrate the potential of this analytical approach and should be viewed as a foundation for future development rather than as emissions allocation guidance.

## What is Tao360 and why should you care?

Each subnet represents a unique AI implementation with its own development trajectory, making network-wide evaluation an increasingly complex endeavor. Tao360 simplifies this process by doing the heavy lifting: it automatically gathers relevant data about each subnet, runs it through multiple AI models using a standardized framework, and delivers quick insights about subnet performance and suggested emissions. A task that would take days of manual research and analysis can now be accomplished in minutes with this streamlined tool.

## How Does It Work?

Tao360 meticulously analyzes the same network from different angles. The process begins by pulling data from the following sources for each subnet:

* GitHub activity to track development progress
* Twitter and Discord engagement to measure community involvement
* Whitepaper and website insights to gauge vision and roadmap
* Real-time network metrics to assess performance
* Historical emissions data to understand resource usage

These diverse data streams are then processed in tandem with the OTF Framework[^1] through several leading AI models (Gemini 1.5 Pro, GPT-4, Claude 3.5 Sonnet and Llama 3). In the short report, each model offers a valuation, suggested emissions, justification, direct quotes to substantiate articulated claims, and next steps. This process is repeated several times to eliminate single-report bias and a consensus report is created for each model which compares and averages the results of the short reports.

![1](https://i.imgur.com/HtxwoxL.jpg)

## A Network-Wide Analysis

Between November 26-30, 2024, we conducted a comprehensive network analysis generating over 2,350 individual reports.This included 11+ short reports per subnet from each AI model, which were then consolidated into consensus reports. Below are the suggested emissions based on this extensive analysis.

![1](https://i.imgur.com/lgqztq8.jpg)

### Key Trends

**Undervaluation Signal**: Subnets deemed undervalued typically demonstrated real-world applications, solid benchmarking progress, active development, and strong community engagement

**Overvaluation Signal**: Subnets marked as overvalued commonly showed network stability problems, particularly around miner and validator operations

**AI Model Assessment Trends**: When analyzing subnets in isolation, AI models generally leaned toward "undervalued" or "appropriate" ratings. As a result, any overvaluation flags carried significant weight in final emissions calculations

![1](https://i.imgur.com/IjUZyNo.jpg)

### Current Limitations

The following are some notable limitations of the current results and methodology:

**Social Media Bias**: Tao360's dependence on social media data from Twitter and Discord may overemphasize social signals in the valuation process, creating potential vulnerabilities. There is also susceptibility to manipulation through artificial discord messages and social activity.

**Benchmark Verification Challenges**: Benchmarking results are primarily verified through social media channels with a lack of direct verification mechanisms.

**Blackbox Evaluation Approach**: While Tao360 can process multiple data streams and generate valuations, it lacks the flexibility to adjust how different factors are weighted in the evaluation process.

## Looking ahead

While Tao360 represents a significant advance in network evaluation, the research team acknowledges there's more work to be done. Below are some future development ideas in the works.

### Planned Improvements

**Adjustable Weighting System**: Development of a flexible framework where evaluation parameters can be tuned based on empirical results and network feedback

**Performance Validation Metrics**: Implementation of quantifiable benchmarks that can be adjusted as the network evolves and different subnet types emerge

**Adaptive Evaluation Criteria**: Creation of subnet-specific evaluation parameters that can be modified based on the subnet's declared purpose and actual performance (i.e grouping of subnets by development category)

### Additional Features Under Consideration

**Subnet Discovery Quiz**: A tailored quiz to recommend subnets based on user interests and priorities. This might be especially useful when Dtao is launched to allow non Bittensor-native users to learn about subnets quickly.

**Comprehensive Setup Guides**: Step-by-step guides for becoming a validator or miner, emphasising ease of set-up.

## The Bottom Line

Tao360 represents an important first step toward more objective and comprehensive network evaluation, even as we acknowledge its current limitations. While the current framework's reliance on social signals and indirect verification presents challenges, its ability to identify patterns across multiple AI models and data sources offers valuable insights for network optimization. The consistent patterns observed in mid-range subnet evaluations and the framework's ability to flag potential misalignments in resource allocation demonstrate the promise of AI-assisted network analysis.

However, what makes Tao360 truly significant isn't just its current capabilities, but what it reveals about the future of network evaluation. As we continue to refine the methodology and incorporate more quantitative metrics, this type of systematic analysis could become an invaluable tool for network governance and resource allocation decisions. While no single evaluation framework may be perfect, combining multiple perspectives through AI analysis can help us better understand and optimize complex decentralized networks.

[^1]: RF-001: "Raomitee Framework Comprehensive Assessment and Evaluation of Subnets in the Bittensor Ecosystem," RFC Document, Bittensor Repository, December 2024