# Frequently Asked Questions

## Fundamentals (Remember & Understand)

### What is supply chain risk management?

Supply chain risk management is the systematic process of identifying, assessing, and mitigating potential disruptions across the network of organizations involved in producing and delivering goods or services. It encompasses risks from suppliers, logistics, natural disasters, geopolitical events, cyber threats, and other sources that could interrupt operations or damage organizational performance.

### What is ISO 28000 and why is it important?

ISO 28000 is an international standard specifying requirements for security management systems in supply chains. It's important because it provides a structured, globally recognized framework for managing supply chain security risks, enabling organizations to systematically identify threats, implement controls, and demonstrate commitment to security through third-party certification.

### What are the main categories of supply chain risk?

The five main categories are:
1. **Operational risks** - supplier failures, quality issues, capacity constraints
2. **Financial risks** - currency fluctuation, supplier insolvency, payment issues
3. **Geopolitical risks** - trade restrictions, political instability, regulatory changes
4. **Environmental risks** - natural disasters, climate change, pandemics
5. **Cyber risks** - ransomware, data breaches, system failures

### What is the difference between safety stock and strategic stock?

Safety stock is inventory held as buffer against normal variability in demand or supply, sized statistically based on standard deviation and desired service levels. Strategic stock is deliberately held excess inventory for specific high-risk components as insurance against known vulnerabilities like single-source dependency or geopolitical exposure, justified by disruption avoidance value rather than statistical optimization.

### What does the PDCA cycle stand for?

PDCA stands for Plan-Do-Check-Act, a cyclical methodology for continual improvement:
- **Plan**: Establish objectives and processes
- **Do**: Implement the plan
- **Check**: Monitor and measure results
- **Act**: Take corrective action and improve

## Application (Apply)

### How do I calculate a Risk Priority Number in FMEA?

The Risk Priority Number (RPN) is calculated by multiplying three factors:

**RPN = Severity × Occurrence × Detection**

- **Severity**: Rate the impact if the failure occurs (1-10 scale)
- **Occurrence**: Rate the likelihood of the failure happening (1-10 scale)
- **Detection**: Rate how difficult it is to detect the failure before impact (1-10 scale)

Higher RPNs indicate greater priority for mitigation. Focus resources on highest RPN items first.

### How much safety stock should I maintain?

Safety stock levels depend on several factors:

**Basic Formula**: Safety Stock = Z × σ × √(Lead Time)

Where:
- Z = service level factor (1.65 for 95%, 2.33 for 99%)
- σ = standard deviation of demand
- Lead Time = replenishment lead time

For high-risk items, consider:
- Using 95th percentile lead time instead of average
- Adding buffer for low-frequency, high-impact disruptions
- Segment by risk level (higher buffers for critical, high-risk components)

### How do I conduct a supplier financial health assessment?

Follow these steps:

1. **Gather financial data**: Credit reports, financial statements, ratings
2. **Calculate key ratios**:
   - Current Ratio (should be >1.5)
   - Debt-to-Equity (concern if >2.0)
   - Operating Margin (declining trend is red flag)
3. **Calculate Altman Z-Score**: Z < 1.81 indicates high bankruptcy risk
4. **Monitor indicators**: Credit rating changes, payment delays, management turnover
5. **Set review frequency**: Quarterly for strategic suppliers, annually for others

### When should I choose single-source vs multi-source suppliers?

Use this decision framework:

**Favor Single-Source when**:
- Component highly customized requiring deep collaboration
- Volume justifies supplier dedication and investment
- Quality consistency critical and supplier proven
- Total cost benefits significant (economies of scale)

**Favor Multi-Source when**:
- Component critical to operations (production stops without it)
- Competitive supplier market with qualified alternatives
- Geographic or geopolitical concentration risk high
- Lead times short enough to enable rapid switching

Many organizations use hybrid "primary + backup" strategies for critical items.

## Analysis (Analyze)

### How do I evaluate the trade-offs between nearshoring and offshoring?

Conduct comprehensive total cost and risk analysis:

**Offshoring Advantages**:
- Lower direct labor costs
- Economies of scale in manufacturing hubs
- Access to specialized capabilities

**Offshoring Disadvantages**:
- Extended lead times (weeks vs days)
- Higher inventory carrying costs
- Transportation complexity and expense
- Geopolitical exposure
- Quality control challenges

**Nearshoring Advantages**:
- Shorter lead times enabling agility
- Lower geopolitical risk
- Easier collaboration and oversight
- Potential total cost competitiveness

**Nearshoring Disadvantages**:
- Higher direct labor costs
- Limited supplier base for some capabilities
- Smaller economies of scale

**Recommendation**: Segment portfolio. Nearshore critical, lead-time-sensitive items. Offshore low-criticality commodities where cost advantage justifies risk and inventory costs.

### What are the limitations of risk matrices?

Risk matrices have several important limitations:

1. **Oversimplification**: Reduce complex scenarios to two dimensions (probability × impact)
2. **Subjectivity**: Different assessors may rate same risks differently
3. **Range compression**: Cannot distinguish fine gradations within categories
4. **Multiplication assumption**: Implies probability and impact combine multiplicatively, which may not reflect reality
5. **Missing dimensions**: Ignore velocity, recovery time, and cascading effects

**Best Practice**: Use risk matrices for initial prioritization and communication, but supplement with detailed quantitative analysis for high-priority risks.

### How does tier-2 supplier visibility improve risk management?

Tier-2 visibility provides several advantages:

**Early Warning**: Many disruptions originate beyond tier-1. Visibility enables detection before impacts cascade downstream.

**Concentration Discovery**: May reveal that multiple tier-1 suppliers share tier-2 dependencies, creating hidden concentration risk.

**Root Cause Analysis**: Understanding deeper tiers enables accurate problem diagnosis rather than treating symptoms.

**Proactive Mitigation**: Can develop direct relationships or alternative tier-2 sources before tier-1 failures occur.

**Example**: Automotive company discovered three tier-1 suppliers all sourced electronics from same tier-2 fab. When fab had fire, all three tier-1 suppliers failed simultaneously. Tier-2 visibility would have revealed concentration and enabled diversification.

## Evaluation (Evaluate)

### How do I assess whether my supply chain is resilient enough?

Evaluate resilience across multiple dimensions:

**Metrics Assessment**:
- Time to Recovery for recent disruptions (improving?)
- Time to Survive for critical components (adequate buffer?)
- Supplier concentration indices (reducing over time?)
- Geographic diversity (adequate spread?)

**Stress Testing**:
- Conduct scenario simulations for major risks
- Evaluate performance under disruption
- Identify breaking points and vulnerabilities

**Capability Assessment**:
- Business continuity plans tested and current?
- Alternative suppliers qualified and contractually ready?
- Control tower visibility operational?
- Crisis management protocols validated?

**Comparative Benchmarking**:
- How did you perform vs competitors during recent disruptions?
- Industry resilience metrics comparison
- Customer feedback on service continuity

**Investment Analysis**:
- What percentage of supply chain budget allocated to resilience vs efficiency?
- ROI on resilience investments (disruptions avoided, faster recovery)

### How do I determine the right balance between efficiency and resilience?

The optimal balance depends on context:

**Factors Favoring Efficiency**:
- Highly competitive, price-sensitive market
- Stable operating environment
- Low consequence of disruptions (non-critical products)
- Strong financial pressure for margin improvement

**Factors Favoring Resilience**:
- High-consequence disruptions (safety-critical, revenue-critical)
- Volatile environment (geopolitical, natural disaster exposure)
- Competitive advantage through reliability
- Board/customer pressure for supply assurance

**Approach**:
1. **Segment portfolio**: Don't use one-size-fits-all. Critical items justify resilience investment; commodities can optimize for cost.
2. **Quantify trade-offs**: Model cost of resilience (inventory, dual-sourcing) vs cost of disruptions (lost revenue, expedited freight, market share loss)
3. **Set risk appetite**: Executive decision on acceptable risk levels
4. **Monitor and adjust**: Review balance annually based on performance and changing conditions

## Creation (Create)

### How do I design a comprehensive business continuity plan for my supply chain?

Follow this structured approach:

**Phase 1: Analysis**
1. Conduct Business Impact Analysis identifying critical functions
2. Assess dependencies (suppliers, facilities, systems, workforce)
3. Define Recovery Time Objectives for each function
4. Identify potential disruption scenarios

**Phase 2: Strategy Development**
5. For each critical function, develop:
   - Preventive controls to reduce likelihood
   - Alternative capabilities (suppliers, facilities, routes)
   - Inventory buffers and capacity reserves
   - Communication and coordination protocols

**Phase 3: Documentation**
6. Create plan documents including:
   - Emergency contacts and decision authorities
   - Step-by-step response procedures
   - Alternative supplier and facility information
   - Resource inventories

**Phase 4: Validation**
7. Conduct tabletop exercises walking through scenarios
8. Test actual execution (call suppliers, verify alternatives work)
9. Identify gaps and refine plan

**Phase 5: Maintenance**
10. Annual review and update
11. Post-incident reviews capturing lessons
12. Continuous improvement based on testing and real events

### How would you build a supply chain control tower from scratch?

**Step 1: Define Scope and Objectives**
- What visibility is needed? (suppliers, logistics, inventory, demand)
- What decisions will the control tower support?
- What functions will participate?
- Physical vs virtual model?

**Step 2: Technology Platform Selection**
- Evaluate visibility platform vendors
- Ensure integration capabilities with existing systems (ERP, WMS, TMS, supplier systems)
- Require dashboard/analytics capabilities
- Consider cloud vs on-premise

**Step 3: Data Integration**
- Identify data sources (internal systems, supplier systems, logistics providers, external feeds)
- Develop integration architecture (APIs, file transfers, manual portals)
- Implement data validation and quality controls
- Start with critical suppliers/lanes, expand progressively

**Step 4: Analytics and Alerting**
- Define KPIs and metrics
- Build dashboards for different user roles
- Configure exception alerts and thresholds
- Implement escalation workflows

**Step 5: Organizational Design**
- Staff control tower (manager, analysts, subject matter experts)
- Define decision authorities and escalation paths
- Create standard operating procedures
- Establish governance and review processes

**Step 6: Pilot and Rollout**
- Start with limited scope (one product line or region)
- Validate capabilities and refine
- Demonstrate value to gain organizational support
- Expand scope progressively

**Step 7: Continuous Improvement**
- Regular performance reviews
- User feedback incorporation
- Expand data sources and analytics
- Evolve based on lessons from disruptions

### How would you develop a supply chain risk mitigation strategy for climate change?

**Assessment Phase**:

1. **Physical Risk Mapping**
   - Map supplier and facility locations
   - Overlay climate risk zones (sea level rise, wildfire, drought, extreme heat, flooding)
   - Assess infrastructure vulnerabilities (ports, transportation routes)
   - Identify geographic concentrations in high-risk areas

2. **Transition Risk Analysis**
   - Evaluate exposure to carbon pricing
   - Assess stranded asset risk (fossil fuel infrastructure)
   - Review customer/investor sustainability requirements
   - Analyze competitive positioning on climate

**Strategy Development**:

3. **Sourcing Decisions**
   - Incorporate climate risk in supplier selection
   - Diversify away from high-risk geographies
   - Require supplier climate adaptation plans
   - Prefer suppliers with lower carbon footprint

4. **Infrastructure Resilience**
   - Harden facilities in high-risk locations (flood protection, fire resistance)
   - Develop redundant facilities in lower-risk regions
   - Assess and reinforce critical infrastructure dependencies

5. **Operational Adaptation**
   - Adjust safety stock for higher variability
   - Develop heat-wave protocols (worker safety, equipment performance)
   - Alternative transportation routes avoiding high-risk corridors

6. **Decarbonization**
   - Set science-based emissions reduction targets
   - Engage suppliers on Scope 3 emissions
   - Optimize transportation mode and routing
   - Transition to renewable energy in operations

**Implementation**:

7. **Integration**
   - Incorporate climate risk into existing risk management frameworks
   - Connect to business continuity planning
   - Include in supplier scorecards and audits

8. **Monitoring**
   - Track climate risk indicators
   - Monitor supplier progress on adaptation
   - Measure emissions reduction progress
   - Regular strategy review and adjustment
