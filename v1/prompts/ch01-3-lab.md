Act as a Principal Infrastructure Architect. Render an INTERACTIVE CAPACITY & SCALE ESTIMATOR WIDGET in HTML/JS/CSS as a self-contained Single Page Application (SPA).

System Baseline Constraints:
- Default DAU: 10 Million (Range: 1M - 100M)
- Peak Voting QPS Multiplier: 10x (Base: 10,000 QPS, Peak: 100,000 QPS)
- Media Upload Compression: 10% thumbnail sizing (5 KB per thumbnail)
- Retention Horizon: 5 Years

Interactive Controls & Sliders:
1. DAU Scale Slider (1M to 100M)
2. Photo Ingress Rate (100 to 2,000 uploads/sec)
3. Retention Period (1 to 10 years)
4. CDN Cache Hit Ratio Toggle (80%, 90%, 95%)

Outputs & Dynamic Calculations:
- Ingress Network Bandwidth (Gbps) & Egress CDN Offload Savings
- IOPS metrics for Redis Cluster and Sharded MySQL
- Total 5-Year Storage Footprint Breakdown: Raw S3 Media (PB) vs Metadata DB (TB)
- Visual Alert Banner when network egress exceeds 10 Gbps interface caps.

Build a clean, responsive, fully working dark-mode UI.