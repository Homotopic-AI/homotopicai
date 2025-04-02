# MAP™ Brick Pricing

<div class="hero-section text-center mb-5">
    <h1 class="display-4 mb-4"><i class="fas fa-dollar-sign"></i> Pay-As-You-Train Model</h1>
    <p class="lead">Revolutionary metering system that precisely quantifies resource consumption based on actual usage.</p>
</div>

<div class="pricing-comparison mb-5">
    <h2>Advantages Over Traditional Models</h2>
    <table class="comparison-table">
        <tr>
            <th>Feature</th>
            <th>Traditional Cloud Billing</th>
            <th>MAP Metering System</th>
        </tr>
        <tr>
            <td>Granularity</td>
            <td>VM-hours or GPU-hours, regardless of load</td>
            <td>Per-core, per-second, precision-adjusted billing</td>
        </tr>
        <tr>
            <td>Fairness</td>
            <td>Users pay for idle time (e.g., unused CPU)</td>
            <td>Pay only for active computation (processing-seconds)</td>
        </tr>
        <tr>
            <td>Energy Transparency</td>
            <td>Opaque power costs bundled into flat rates</td>
            <td>Net energy consumption with reversible credits</td>
        </tr>
        <tr>
            <td>Security Premiums</td>
            <td>Uniform storage costs, even for encrypted data</td>
            <td>Variable rates for encrypted/homomorphic storage</td>
        </tr>
    </table>
</div>

<div class="pricing-details mb-5">
    <h2>Core Type Pricing</h2>
    <div class="pricing-cards">
        <div class="pricing-card">
            <h3>Tensor Cores</h3>
            <p class="price">$0.001</p>
            <p>per tensor-second (FP32)</p>
        </div>
        <div class="pricing-card">
            <h3>Symbolic Cores</h3>
            <p class="price">$0.005</p>
            <p>per symbolic-second (exact arithmetic premium)</p>
        </div>
        <div class="pricing-card">
            <h3>Stochastic Cores</h3>
            <p class="price">$0.0005</p>
            <p>per Monte Carlo trial</p>
        </div>
    </div>
</div>

<div class="pricing-options mb-5">
    <h2>Additional Services</h2>
    
    <h3>Precision Scaling</h3>
    <ul class="feature-list">
        <li><i class="fas fa-check"></i> 4-bit POSIT: <strong>50% discount</strong> vs. FP32</li>
        <li><i class="fas fa-check"></i> 128-bit exact arithmetic: <strong>200% premium</strong> for cryptographic tasks</li>
    </ul>

    <h3>Memory/Storage</h3>
    <ul class="feature-list">
        <li><i class="fas fa-check"></i> Hypergraph memory: <strong>$0.01 per RMU-hr</strong></li>
        <li><i class="fas fa-check"></i> Encrypted MOS: <strong>$0.03 per GB-hr</strong> (lattice-based encryption)</li>
    </ul>
</div>

<div class="metering-components mb-5">
    <h2>Metering Components</h2>
    
    <div class="component-cards">
        <div class="component-card">
            <h3>Processing-Seconds</h3>
            <p><strong>Definition:</strong> Time (in seconds) a specific MAP core is actively executing a task.</p>
            <p><strong>Measurement:</strong></p>
            <ul>
                <li>Core-Specific Clocks: Each core has dedicated hardware counters to track active cycles</li>
                <li>Dynamic Precision Scaling: Tasks using lower precision consume fewer "effective processing-seconds"</li>
            </ul>
            <div class="example-box">
                <h4>Example:</h4>
                <p>A tensor core running a matrix multiplication in FP32 for 10 seconds = 10 FP32 tensor-seconds</p>
                <p>The same task in 8-bit POSITs completes in 2 seconds = 2 POSIT-8 tensor-seconds</p>
            </div>
        </div>
        
        <div class="component-card">
            <h3>Memory Usage</h3>
            <p><strong>Definition:</strong> Amount of hypergraph memory allocated during computation.</p>
            <p><strong>Measurement:</strong></p>
            <ul>
                <li>Relational Memory Units (RMUs): Memory is billed per gigabyte-hour based on the complexity of stored hypergraphs</li>
                <li>Sparse vs. Dense: Sparse data incurs lower costs due to compression</li>
            </ul>
            <div class="example-box">
                <h4>Example:</h4>
                <p>Storing a 100GB social network hypergraph for 1 hour = 100 RMU-hr</p>
                <p>Compressed sparse tensor storage reduces this to 20 RMU-hr</p>
            </div>
        </div>
        
        <div class="component-card">
            <h3>Storage</h3>
            <p><strong>Definition:</strong> Long-term retention of data in MAP-optimized formats.</p>
            <p><strong>Measurement:</strong></p>
            <ul>
                <li>Mathematical Object Storage (MOS): Costs scale with precision and structure</li>
                <li>Exact Arithmetic Storage: Fixed cost for 256-bit cryptographic primes</li>
                <li>Lossless Compression: Symbolic expressions stored as syntax trees</li>
            </ul>
            <div class="example-box">
                <h4>Example:</h4>
                <p>Storing a 1TB encrypted dataset with homomorphic encryption = 1TB × 2× MOS rate (security premium)</p>
            </div>
        </div>
    </div>
</div>

<div class="business-model mb-5">
    <h2>Revenue Model (Pay-As-You-Train)</h2>
    <div class="model-card">
        <p>Instead of one time fees and subscriptions, we partner with companies on a revenue share model and cover the Math Aware Processor device CAPEX moving the cost of computing to OPEX.</p>
        <div class="model-features">
            <i class="fas fa-coins"></i>
            <p>Pay-per-use metering system for Math-Aware Processors (MAPs) revolutionizes computational billing by precisely quantifying resource consumption based on exact processing-seconds, memory, and storage used.</p>
        </div>
        <div class="highlight-box">
            <p>This system leverages the unique architectural features of MAPs, like adaptive precision, domain-specific cores, hypergraph memory, to create a granular, transparent, and fair billing model.</p>
        </div>
    </div>
</div>
