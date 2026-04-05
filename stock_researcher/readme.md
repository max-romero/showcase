<style>
  .solution-container {
    font-family: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
    max-width: 900px;
    margin: 0 auto;
    padding: 2rem;
    background: linear-gradient(135deg, #f8fafc 0%, #eef2ff 100%);
    border-radius: 2rem;
    line-height: 1.6;
    color: #0f172a;
  }

  .section-title {
    font-size: 1.8rem;
    font-weight: 700;
    margin-top: 2rem;
    margin-bottom: 1rem;
    padding-bottom: 0.5rem;
    border-bottom: 4px solid;
    display: inline-block;
  }

  .section-title.overview {
    color: #1e3a8a;
    border-bottom-color: #3b82f6;
  }

  .section-title.ai {
    color: #7e22ce;
    border-bottom-color: #a855f7;
  }

  .card {
    background: white;
    border-radius: 1.5rem;
    padding: 1.5rem;
    margin: 1.5rem 0;
    box-shadow: 0 10px 25px -5px rgba(0, 0, 0, 0.05), 0 8px 10px -6px rgba(0, 0, 0, 0.02);
    transition: transform 0.2s ease, box-shadow 0.2s ease;
  }

  .card:hover {
    transform: translateY(-2px);
    box-shadow: 0 20px 30px -12px rgba(0, 0, 0, 0.1);
  }

  .agent-card {
    border-left: 6px solid;
    background: #ffffff;
  }

  .agent-card.analysis {
    border-left-color: #3b82f6;
  }

  .agent-card.sentiment {
    border-left-color: #a855f7;
  }

  .agent-title {
    font-size: 1.35rem;
    font-weight: 700;
    margin-bottom: 0.75rem;
    display: flex;
    align-items: center;
    gap: 0.5rem;
  }

  .agent-title .badge {
    font-size: 0.7rem;
    font-weight: 600;
    padding: 0.2rem 0.6rem;
    border-radius: 2rem;
    background: #e2e8f0;
    color: #1e293b;
  }

  .agent-title .badge.primary {
    background: #dbeafe;
    color: #1e40af;
  }

  .agent-title .badge.secondary {
    background: #f3e8ff;
    color: #6b21a5;
  }

  .highlight {
    background: linear-gradient(120deg, #eff6ff 0%, #eff6ff 40%, transparent 80%);
    padding: 0 0.2rem;
    font-weight: 500;
    color: #1e3a8a;
  }

  .feature-list {
    list-style: none;
    padding-left: 0;
  }

  .feature-list li {
    margin: 0.75rem 0;
    padding-left: 1.5rem;
    position: relative;
  }

  .feature-list li::before {
    content: "✓";
    position: absolute;
    left: 0;
    color: #3b82f6;
    font-weight: bold;
  }

  hr {
    margin: 2rem 0;
    border: 0;
    height: 1px;
    background: linear-gradient(90deg, transparent, #cbd5e1, transparent);
  }

  @media (max-width: 640px) {
    .solution-container {
      padding: 1rem;
    }
    .section-title {
      font-size: 1.4rem;
    }
  }
</style>

<div class="solution-container">

# Sample
File `stock_analysis_20260404` in stock_research folder

# Frequency
Weekly generation

# Available Reports
USA (NYSE + NASDAQ)
  Oversold
  Overbought

# Solution Overview

<div class="card">
This solution provides an <span class="highlight">automated stock research and analysis platform</span> that identifies investment opportunities through systematic screening and AI-powered evaluation. The system addresses the challenge of efficiently analyzing thousands of stocks by combining quantitative filtering with qualitative AI assessment.

It streamlines the investment research process from data collection to actionable insights, reducing manual effort while maintaining analytical rigor. The platform identifies oversold and overbought stocks based on technical indicators and fundamental metrics, then enriches these candidates with market sentiment and investment principle analysis.

By automating the data pipeline and applying consistent evaluation criteria, it enables <span class="highlight">systematic investment decision-making</span>. The solution delivers professional-grade research reports in accessible formats, making sophisticated analysis available to investors without requiring extensive financial expertise or time commitment.
</div>

## AI Application

<div class="card">
The solution employs <span class="highlight">two specialized AI agents</span> working in sequence to transform raw stock data into investment insights:
</div>

<div class="agent-card analysis">
  <div class="agent-title">
    Stock Analysis Agent 
    <span class="badge primary">Primary Agent</span>
  </div>
  <p>This primary agent analyzes filtered stock candidates by applying investment principles to quantitative metrics. It evaluates each stock's financial health, valuation, and growth prospects without naming specific investors, focusing instead on the underlying principles of value and growth investing. The agent generates natural language analysis that assesses investment merit while honestly acknowledging risks and concerns.</p>
</div>

<div class="agent-card sentiment">
  <div class="agent-title">
    Market Sentiment Agent 
    <span class="badge secondary">Context Agent</span>
  </div>
  <p>Operating alongside the analysis agent, this component scans recent news and market developments to provide current sentiment context. It summarizes relevant financial news without applying bullish/bearish labels, instead describing what the news indicates about market perception. This agent ensures the analysis incorporates both quantitative metrics and qualitative market context for a more complete investment picture.</p>
</div>

<hr>

# Pricing
April 2026: USD 1 (one) per requested report

# Suscription
On-demand. 
Reports are generated during Friday night and delivered to subscribers during Saturday early morning.

**SUBSCRIBE TO NEXT RUN (April 10, 2026)**

- [Subscribe to Oversold](mailto:romero_maxi@outlook.com?subject=Stock%20Researcher%20Oversold)
- [Subscribe to Overbought](mailto:romero_maxi@outlook.com?subject=Stock%20Researcher%20Overbought)
- [Subscribe to Both](mailto:romero_maxi@outlook.com?subject=Stock%20Researcher%20Oversold%2BOverbought)

</div>