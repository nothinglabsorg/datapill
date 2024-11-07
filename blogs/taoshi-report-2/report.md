# Taoshi: Trading Alpha on Bittensor

**Authors:** [Sami Kassab](https://x.com/Old_Samster) and [Brody Adreon](https://x.com/brodyadreon)
*Nov. 5, 2024
Download [PDF](https://drive.google.com/file/d/1C9P_ebErLTOKMg_nHuajRBdUMwpiQTA2/view?usp=sharing)

### Key Insights

-   The Proprietary Trading Network (Subnet 8) distributes over $50,000 in daily rewards to participants generating actionable trade signals across forex, crypto, and stock indices.
    
-   Aggregating performance across all participating traders on the subnet through a weighted scoring system, the network achieved 90-day returns averaging 4.7% with an average drawdown of 3%.
    
-   Taoshi's upcoming Glitch platform represents a significant step toward mainstream adoption of the subnet’s outputs, enabling users to seamlessly execute institutional-grade trading strategies through a non-custodial solution.


Taoshi's Proprietary Trading Network, better known as Bittensor subnet 8, is a decentralized platform where trading and machine learning professionals compete to provide institutional-grade trading signals across forex, stock indices, and crypto assets. The subnet operates as a continuous, transparent proprietary trading competition, rewarding contributors for producing competitive trading signals, while making these insights accessible to all.

And the rewards are substantial: a daily incentive pool of $52,000 (based on a TAO price of $525 at the time of writing) awaits those brave enough to enter the arena.

By creating a decentralized marketplace for actionable trading insights, the Proprietary Trading Network (PTN) aims to democratize access to sophisticated and continuously evolving trading strategies through open-source contributions and competition.

## Background

Established in October 2023, the PTN stands as the third oldest subnet on Bittensor. Founded by Arrash Yasavolian, who previously led TARVIS Labs developing algorithmic trading models, PTN initially focused on incentivizing time-series prediction for financial markets. However, this objective proved challenging, as building effective machine learning-based prediction models required vast data and algorithmic advancements that would take years to develop.

Seeking to create more immediate value, Yasavolian redirected the subnet's focus to actionable trading signals in March 2024. Since this pivot, Taoshi, the company behind PTN, has grown to include 16 full-time team members, and the subnet has distributed hundreds of thousands of TAO to contributors, successfully attracting machine learning and trading professionals to its network.

## Market Assessment

As financial markets become more efficient, traders and asset managers are under increasing pressure to find a competitive edge, driving demand for superior strategies, better data, and additional resources. The PTN's potential to become the canonical venue for accessible, high-quality trading signals is underscored by three developing trends: growing adoption of AI, shift in capital allocation, and the rise of decentralized networks.

While consumer AI applications like ChatGPT steal the spotlight, Wall Street is facing increasing pressures to adopt AI, as it's becoming clear that these tools are effective at generating superior returns and allocating capital.

Although quant funds have traditionally underperformed over longer investment horizons, recent data shows this trend is reversing. According to data from Aurum, quant strategies are outperforming competing hedge fund strategies and posted an impressive [8.7%](https://www.aurum.com/hedge-fund-data/hedge-fund-industry-deep-dive/hedge-fund-industry-performance-deep-dive-h1-2024/) average YTD return since June 2024.

![1](https://i.imgur.com/Reuq8WN.jpeg)

Meanwhile, markets are becoming increasingly automated, with algorithmic trading now widely [adopted](https://www.businessinsider.com/wall-street-goldman-jpmorgan-bridgewater-using-ai-2023-12) by major financial institutions, and AI strategies being [rapidly](https://www.reuters.com/markets/markets-ai-efficiency-may-bring-volatility-mcgeever-2024-10-17/#:~:text=The%20financial%20industry,could%20be%20coming.) integrated into these algorithms. Consequently, both trends are expected to intensify and intersect with the advent of AI agents, effectively verticalizing trading strategy creation and capital allocation workflows.

Alongside these trends is the proliferation of decentralized networks, which excel at coordinating geographically distributed participants through crypto-economic incentives. The effective alignment of these incentives creates capital and talent vacuums, fostering stronger competition that leads to better outcomes and, in the PTN’s case, trading signals.

### Competitive Landscape

Validating PTN’s market opportunity is the emergence of market prediction competitions and other crypto networks aiming to crowd-source trading or market prediction insights, whether for proprietary purposes or democratized access.

For example, Jane Street recently launched a Kaggle [competition](https://www.kaggle.com/competitions/jane-street-real-time-market-data-forecasting/overview) offering a $50,000 prize for the best real-time market data forecasting model using their proprietary datasets, with a total of $100,000 in rewards available. However, with closed-source competitions such as Kaggle, participants face rigid platform constraints that limit collaboration, innovation, and ownership rights, creating an environment that prioritizes procedural compliance over creative exploration. Even though Jane Street recognizes the value of open competitions and collective intelligence, the structural limitations of such platforms hinder their full potential. In comparison, PTN offers rewards of similar magnitude every day, making its decentralized competition significantly more attractive to contributors.

Alongside Jane Street, Allora Network, a decentralized network crowd-sourcing asset-specific price predictions, incentivizes participation with its own token. Allora's protocol design, while strikingly similar to Bittensor's subnet architecture, is still unproven as the network is still in its testnet and has yet to overcome the challenge of attracting sustained quality participation.

Separating PTN from the solutions outlined above is its direct link to Bittensor, the most proven AI coordination protocol to date, with a robust stream of recurring rewards and deep talent moat. As such, PTN inherits immediate network effects while offering miners reliable opportunities to monetize their strategies, avoiding the rigid constraints of centralized platforms like Kaggle and effectively solving the cold start problem that plagues new networks like Allora.

As markets become more automated and competitive, PTN's capacity to harness collective intelligence via crypto-economic incentives positions it to be a promising marketplace for both signal providers looking to monetize their strategies and traders seeking sustainable alpha in a dynamic market.

## Subnet Inner Workings

### Mining

At the heart of the PTN sit the miners, the participants responsible for generating actionable trade signals - indicators to buy, sell, or hold an asset. These trade signals take the form of straightforward long or short position orders for specific trade pairs. The simplicity of this deliverable offers two key advantages:

1.  Strategy Agnosticism: The subnet remains indifferent to the methods miners employ to produce their trade signals. Whether utilizing machine learning models or manual quant methods, all approaches are accepted.
    
2.  IP Protection: By asking for only the final trade signal from miners, the subnet safeguards the proprietary nature of each miner's strategy, encouraging participation from skilled traders and institutions who might otherwise be hesitant to share their methods.
    

While it is difficult to determine the exact strategies miners use—since the network does not require them to reveal this information—interviews with several miners indicate a mix of AI-driven and traditional approaches. One miner disclosed that they generate signals using a third-party ML algorithm combined with a homegrown heuristic model, describing their overall approach as mean reversion with heavy reliance on confluence and strategic risk management. Another miner reported using a non-AI strategy that blends indicators across multiple timeframes, focusing on trend direction, momentum, and volatility, among other factors.

### Validating

On the other side of the equation, validators play an equally crucial role. They employ a risk-adjusted scoring system, designed and maintained by Taoshi, to evaluate miners’ submissions, ranking them based on their performance.

The outcome is a dynamic leaderboard that objectively ranks miner performance and directly ties results to rewards, creating a competitive environment that continuously incentivizes miners to refine and improve their strategies.

What sets PTN’s validation system apart is its objectivity and simplicity compared to many other Bittensor subnets. This is made possible by the use of real market performance as a benchmark for miner trade signals. The validators operate software that connects to financial data providers via an oracle, giving them real-time access to asset prices and allowing them to accurately measure each miner’s returns.

Beyond performance tracking, validators also monitor for plagiarism and dishonest behavior among miners. Taoshi’s [Plagiarism Detection System](https://x.com/taoshiio/status/1848417892179624345) supports this effort, analyzing miners’ outputs to detect any copying. Miners found plagiarizing are removed from the network. Notably, Taoshi’s plagiarism detection can be utilized across all time-series prediction subnets, enhancing integrity across the ecosystem.

### Scoring and Reward System

PTN’s scoring system goes beyond simple profit metrics, incorporating factors such as consistency, drawdown management, and risk-adjusted returns. More specifically, miners are scored on the following [metrics](https://docs.taoshi.io/ptn/miner/overview/#:~:text=Portfolio%20Value.-,Scoring%20Metrics,-We%20use%20four) listed in order of importance: long term realized returns, short term realized returns, sharpe ratio, and omega ratio.

The scoring system directly influences the reward distribution, which is structured to account for each miner’s relative performance. High-ranking miners receive a greater share of rewards through a skewed [distribution](https://docs.taoshi.io/tips/p11/). Specifically, the top 10% of miners capture 56% of total rewards, while those lower on the leaderboard still earn meaningful incentives to encourage continuous strategy improvement.

![2](https://i.imgur.com/mnfMKVf.jpeg)

To simulate real-world trading conditions, the system incorporates a layer of [costs](https://docs.taoshi.io/ptn/miner/overview/#:~:text=25%25-,Scoring%20Penalties,-There%20are%20four) and [penalties](https://docs.taoshi.io/ptn/miner/overview/#:~:text=proposal%209.-,Fees%20and%20Transaction%20Costs,-We%20want%20to), alongside elimination criteria, such as a drawdown limit, to remove underperforming miners from the competition.

## PTN Performance

The PTN maintains a competitive ecosystem, ensuring a constant push for excellence. As new miners enter the network, the lowest-performing miner is dropped to make room.

The subnet’s scoring system is designed to reward sustained, consistent performance. Long-term returns, measured over a 90-day period, carry the highest weight in the scoring algorithm. This approach incentivizes miners to develop strategies focused on consistent and sustainable returns rather than short-term gains, aligning with the needs of serious traders and investors.

Performance metrics reveal the effectiveness of PTN's incentive mechanism. Recent data shows the typical 90-day return across miners has averaged 4.7% over the past month, calculated as a weighted average based on miner scores.

![3](https://i.imgur.com/zx0ZxF9.jpeg)

The same analysis reveals an average drawdown of 3%. With the scoring system heavily prioritizing drawdown management, many miners have steered clear of highly volatile assets like Bitcoin. One miner noted that the scoring system could be improved to incentivize trading in more volatile markets.

![4](https://i.imgur.com/cUIQFpz.jpeg)

To put these figures into perspective, the HFR Fund-Weighted Composite Index, a broad measure of hedge fund performance, had an annualized return of just [4.0%](https://blogs.cfainstitute.org/investor/2024/06/26/hedge-funds-a-poor-choice-for-most-long-term-investors/) for the 15 years ending June 30, 2023. PTN's 90-day performance of 4.7% not only outpaces this long-term industry benchmark but does so by a substantial margin. Furthermore, PTN's 3% average drawdown is significantly lower than typical drawdowns seen in many traditional and crypto markets, underscoring the effectiveness of its risk management strategies.

## PTN Traction and Usage

PTN's outputs serve two primary functions: direct signal access from miners, and the development of value-added services that transform these signals into refined trading products.

[Timeless](https://x.com/Timeless_io) exemplifies the direct approach through their paid telegram channel, where they selectively share specific trades from top-performing miners. In contrast, Taoshi's [Network Model](https://docs.taoshi.io/reference/networkmodel/) demonstrates the value-added approach, combining miners' signals into a unified strategy that they can offer to consumers.

Current adoption, while limited, shows promising potential across both retail and institutional sectors. Early retail implementations include Timeless's signal distribution and [TaoBot Labs'](https://x.com/TaoBotLabs) experimental trading bots. On the institutional front, Taoshi is spearheading adoption through their new platform, Glitch.

### Glitch

Glitch represents a significant step toward mainstream adoption of PTN's capabilities. This SaaS platform enables users to integrate AI-based trading strategies into their exchange and brokerage accounts through a non-custodial, streamlined process. By incorporating Taoshi’s Network Model that uses the PTN, Glitch aims to democratize wealth generation by making institutional-grade trading strategies accessible to a broader audience.

## The PTN Token

### The Shift to Subnet-Specific Tokens

The upcoming [Dynamic TAO](https://docs.taoshi.io/ptn/miner/overview/#:~:text=Portfolio%20Value.-,Scoring%20Metrics,-We%20use%20four) (dTAO) upgrade, slated for implementation by the end of this year, introduces subnet-specific tokens, fundamentally altering the reward and staking mechanisms across the network.

Currently, subnet contributors receive rewards in TAO, and validators must stake TAO to participate in the network and access subnet outputs. The dTAO upgrade will transition this system to use subnet-specific tokens, creating a more tailored economic model for each subnet.

### Understanding Bandwidth and the PTN Token

Access to subnet services, or 'bandwidth,' forms the foundation of subnet token value. In PTN, as with every Bittensor subnet, validators serve as the gateway to miner outputs. A validator's bandwidth - their level of access to miners - is proportional to their token holdings.

![5](https://i.imgur.com/wQEkL3k.jpeg)

The forthcoming PTN token will determine validators' access to the network's trade signals through a tiered bandwidth system. The validator with the highest token stake will receive access to all miner signals, while subsequent validators will have access to progressively fewer top signals based on their relative stake. While specific implementation details are still being defined, this mechanism creates natural competition among validators to increase their bandwidth by acquiring more tokens.

This model positions validators as the primary source of demand for PTN tokens. For example, Taoshi will run a validator for their platform Glitch to access the subnet. If they aim for the highest access level, they will need to acquire and stake the most PTN tokens. Similarly, any competing platform seeking comparable access must establish a validator and stake PTN tokens to the subnet.

The economic model operates on a straightforward principle: validators will continue to acquire and stake PTN tokens as long as the value derived from trade signals exceeds token acquisition costs. The result is a self-balancing system where token demand directly reflects the perceived value of PTN's outputs.

## Challenges

### Overarching Concerns

Arguably the most economically advantageous problem to crack is predicting financial markets with certainty. Yet, history has shown this problem remains unsolved, raising doubts about whether a solution is truly achievable. As such, there are inherent challenges with this problem space and PTN’s ability to make its mark.

The fundamental challenge of predicting financial markets stems from their inherent complexity and chaotic attributes. Markets represent a vast network of human decisions, emotional responses, and interconnected variables that defy consistent modeling.

Even when patterns emerge, their identification and subsequent exploitation by traders leads to their rapid dissolution - ironically, the very act of democratizing trading signals inherently diminishes their value as "alpha," since true alpha by definition requires an advantage not widely known or accessible.

This creates a paradox where successful strategies become self-defeating once widely known, making traders reluctant to share effective signals and creating an inherent tension between individual advantage and collective knowledge sharing. This cycle, combined with the market's ability to rapidly incorporate new information and adapt to changing conditions, makes sustained predictive accuracy extraordinarily difficult to achieve.

### Technical Concerns

Furthermore, PTN encounters several specific technical constraints in addressing these market dynamics. Its architecture enforces strict drawdown limits and consistency requirements that may inadvertently filter out strategies that, while volatile, could prove valuable in certain market conditions.

The network's limitation to unidirectional trades and position restrictions (one per trade pair) artificially constrains strategy development, while leverage caps of 0.5x for crypto and 5x for forex/indices potentially limit returns during high-conviction opportunities.

Its incentive structure, though designed to reward consistent performance, may inadvertently encourage conservative approaches that underperform in volatile markets. Additionally, the real-time evaluation and automated pruning of strategies, while necessary for risk management, could potentially eliminate approaches that require longer time horizons to demonstrate their effectiveness.

## Final Thoughts

Subnet management requires constant refinement of incentive mechanisms, a responsibility that Taoshi has consistently embraced. Their next phase of development focuses on integrating new risk mitigation techniques into the subnet’s scoring criteria, incorporating auxiliary data such as per-order risk and behavioral categorization. These enhancements will enable more comprehensive evaluation of miners' performance, strengthening the subnet's risk management capabilities and improving the reliability of its outputs.

While "democratizing alpha" is not without its challenges, PTN offers a promising iteration of this experiment, with potential validation on the horizon through Glitch. The PTN has already succeeded in attracting skilled contributors to produce high-quality trading signals, making it the largest reward pool for those seeking to develop cutting-edge forecasting models or signals.

The PTN stands as a model for subnet development within the Bittensor ecosystem. The Taoshi team's commitment to excellence is evident across multiple dimensions: continuous refinement of incentive mechanisms, robust community engagement, and development of applications on top of their subnet. Their contributions extend beyond their subnet, enriching the broader Bittensor ecosystem through crucial infrastructure developments such as the Plagiarism Detection System and the Request Network—establishing standards that benefit the entire network.

As the subnet continues to mature and attract more participants, PTN appears well-positioned to achieve its vision of becoming the canonical venue for accessible, high-quality trading signals in an increasingly algorithmic financial landscape.

_________________________________________________________________

*This report was commissioned by Taoshi. All content was produced independently by the author(s) and does not necessarily reflect the opinions of the organization that requested the report. The commissioning organization does not influence editorial decision or content. This report is meant for informational purposes only. It is not meant to serve as investment advice. You should conduct your own research, and consult an independent financial, tax, or legal advisor before making any investment decisions.*
