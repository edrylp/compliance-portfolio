<script setup>
// No script needed
</script>

<template>
  <!-- Landing -->
  <section id="landing" class="landing-section">
    <div class="container mx-auto">
      <div class="row align-items-center">
        <div class="col-lg-9 mx-auto text-center">
          <h1 class="landing-title mb-3">
            Complete a Risk Profile
          </h1>

          <p class="landing-subtitle mx-auto" style="max-width: 850px;">
            Developed a comprehensive organizational risk profile for a fictional
            specialty coffee shop by identifying financial, operational,
            reputational, and compliance risks while recommending practical
            mitigation strategies to reduce business exposure.
          </p>
        </div>
      </div>
    </div>
  </section>

  <!-- Main Content -->
  <section id="project-details" class="project-section py-5">
    <div class="container" style="max-width: 900px;">

      <!-- Overview -->
      <div class="mb-5">
        <h2 class="h3 section-heading border-bottom pb-2 mb-3">
          Project Overview
        </h2>

        <p>
          As part of the Regulatory Compliance Specialization, I created a
          fictional business and developed a complete organizational risk
          profile. The project required identifying potential risks that could
          impact business operations and recommending practical mitigation
          strategies based on compliance and risk management principles.
        </p>

        <p>
          I chose to create <strong>The Anxious Bean</strong>, a specialty coffee
          shop based in the Philippines, and evaluated risks across four major
          categories: financial, operational, reputational, and compliance.
        </p>

        <div class="p-4 bg-light rounded border-start border-4 border-primary mt-4">
          <h5 class="fw-bold mb-2">The Objective</h5>

          <p class="mb-0 text-muted">
            Develop a structured risk profile that identifies potential threats
            to the organization and proposes mitigation strategies that support
            operational resilience and regulatory compliance.
          </p>
        </div>
      </div>

      <!-- Company -->
      <div class="mb-5">
        <h2 class="h3 section-heading border-bottom pb-2 mb-3">
          Company Profile
        </h2>

        <table class="table table-bordered">
          <tbody>
            <tr>
              <th width="30%">Company</th>
              <td>The Anxious Bean</td>
            </tr>

            <tr>
              <th>Industry</th>
              <td>Food & Beverage</td>
            </tr>

            <tr>
              <th>Overview</th>
              <td>
                A fictional specialty coffee shop in the Philippines offering
                handcrafted coffee, pastries, and a membership rewards program
                in a relaxed and welcoming environment.
              </td>
            </tr>
          </tbody>
        </table>
      </div>

      <!-- Risk Assessment -->
      <div class="mb-5">

        <h2 class="h3 section-heading border-bottom pb-2 mb-3">
          Risk Assessment
        </h2>

        <div class="accordion" id="riskAccordion">

          <!-- Financial -->
          <div class="accordion-item">
            <h2 class="accordion-header">
              <button
                class="accordion-button"
                type="button"
                data-bs-toggle="collapse"
                data-bs-target="#financial">
                <strong>Financial Risks</strong>
              </button>
            </h2>

            <div id="financial" class="accordion-collapse collapse show">
              <div class="accordion-body">

                <h6 class="fw-bold">Inflation</h6>

                <p>
                  Rising ingredient costs may reduce profitability and require
                  pricing adjustments.
                </p>

                <strong>Mitigation</strong>

                <ul>
                  <li>Constantly monitor market and supplier price trends.</li>
                  <li>Source from multiple approved and reputable suppliers to get the best pricing.</li>
                  <li>Look for long-term contracts for better pricing.</li>
                  <li>Adjust menu pricing if needed, offer seasonal drinks and non coffee beverages.</li>
                </ul>

                <hr>

                <h6 class="fw-bold">
                  Cash Flow Instability
                </h6>

                <p>
                  Daily sales might fluctuate due to weather, holidays, and other factors. Low sales might affect ability to cover salaries, rent, ingredients and others.
                </p>

                <strong>Mitigation</strong>

                <ul>
                  <li>Monitor and track daily sales for easier analysis.</li>
                  <li>Implement loyalty programs.</li>
                  <li>Partner with delivery platforms.</li>
                </ul>

              </div>
            </div>
          </div>

          <!-- Operational -->

          <div class="accordion-item">

            <h2 class="accordion-header">

              <button
                class="accordion-button collapsed"
                data-bs-toggle="collapse"
                data-bs-target="#operational">

                Operational Risks

              </button>

            </h2>

            <div id="operational" class="accordion-collapse collapse">

              <div class="accordion-body">

                <h6 class="fw-bold">
                  Power Outages
                </h6>

                <p>
                  The country is prone to typhoons which could lead to power outages. Unexpected power interruptions due to typhoons or local outage can disrupt store operations.
                </p>

                <strong>Mitigation</strong>

                <ul>
                  <li>Maintain a generator to remain in operation even when power is not available.</li>
                  <li>UPS system for POS and computer/s to prevent data loss.</li>
                  <li>Train staff on how to handle power outage situations.</li>
                </ul>

                <hr>

                <h6 class="fw-bold">
                  Equipment Failure
                </h6>

                <p>
                  POS or coffee equipment failures may disrupt service operations.
                </p>

                <strong>Mitigation</strong>

                <ul>
                  <li>Have a regular maintenance schedule for POS and equipment</li>
                  <li>Source equipment from reliable brands with after sales support.</li>
                  <li>Train baristas on proper handling and troubleshooting.</li>
                  <li>Train baristas on how to do manual order taking as a backup.</li>
                </ul>

              </div>

            </div>

          </div>

          <!-- Reputation -->

          <div class="accordion-item">

            <h2 class="accordion-header">

              <button
                class="accordion-button collapsed"
                data-bs-toggle="collapse"
                data-bs-target="#reputation">

                Reputational Risks

              </button>

            </h2>

            <div id="reputation" class="accordion-collapse collapse">

              <div class="accordion-body">

                <h6 class="fw-bold">
                  Pet-Friendly Policy
                </h6>

                <p>
                  Poorly managed pet policies may create customer complaints.
                </p>

                <strong>Mitigation</strong>

                <ul>
                  <li>Have signs available that the store is pet friendly but ensure that pet owners are responsible for any damages.</li>
                  <li>Have a designated pet-friendly space.</li>
                  <li>Cleaning tools should always be available and ready.</li>
                </ul>

                <hr>

                <h6 class="fw-bold">
                  Long Customer Stays
                </h6>

                <p>
                  Extended occupancy may reduce seating availability.
                </p>

                <strong>Mitigation</strong>

                <ul>
                  <li>Have a designated zone for work/study and casual dining.</li>
                  <li>Train staff on how to communicate politely and handle escalation.</li>
                  <li>Have time-limit guidelines during peak hours.</li>
                </ul>

              </div>

            </div>

          </div>

          <!-- Compliance -->

          <div class="accordion-item">

            <h2 class="accordion-header">

              <button
                class="accordion-button collapsed"
                data-bs-toggle="collapse"
                data-bs-target="#compliance">

                Compliance Risks

              </button>

            </h2>

            <div id="compliance" class="accordion-collapse collapse">

              <div class="accordion-body">

                <h6 class="fw-bold">
                  Data Privacy Act of 2012 (RA 10173)
                </h6>

                <p>
                  Collection of membership information requires proper handling
                  of personal data.
                </p>

                <strong>Mitigation</strong>

                <ul>
                  <li>Make sure that customers are aware of what data is being collected and how it will be used.</li>
                  <li>Privacy Notice should be available.</li>
                  <li>Ensure customer data is secure and limited to authorized personnel only.</li>
                </ul>

                <hr>

                <h6 class="fw-bold">
                  Senior Citizen & PWD Discounts (RA 9994 & RA 10754)
                </h6>

                <p>
                  Compliance with mandatory discounts under Philippine law.
                </p>

                <strong>Mitigation</strong>

                <ul>
                  <li>Train staff about the procedure on how to honor and validate discounts.</li>
                  <li>POS can be configured to automatically apply discounts for Senior Citizens and PWDs.</li>
                  <li>Documentation is essential to ensure compliance.</li>
                </ul>

                <hr>

                <h6 class="fw-bold">
                  Food Safety & Sanitation (RA 10611 and PD 856)
                </h6>

                <p>
                  Pet-friendly operations introduce additional sanitation
                  considerations that must comply with food safety regulations.
                </p>

                <strong>Mitigation</strong>

                <ul>
                  <li>Designated pet-friendly space should be far from the food preparation area.</li>
                  <li>Strict guidelines for pet owner regarding pet supervision and sanitation.</li>
                  <li>Conduct routine inspections to stay compliant with sanitation laws.</li>
                  <li>Staff should be trained on sanitation protocols.</li>
                </ul>

              </div>

            </div>

          </div>

        </div>

      </div>

      <!-- Learning -->
      <div class="mb-5">

        <h2 class="h3 section-heading border-bottom pb-2 mb-3">
          Key Learning
        </h2>

        <p>
          This project strengthened my understanding of enterprise risk
          management by demonstrating how financial, operational,
          reputational, and compliance risks are interconnected. It also
          reinforced the importance of identifying potential threats early,
          evaluating their business impact, and implementing practical
          mitigation strategies that support long-term organizational
          resilience.
        </p>

      </div>

      <!-- Disclaimer -->

      <div class="blockquote-custom p-4 bg-light border-start border-3 border-secondary rounded">

        <p class="small text-muted mb-0">

          <strong>Academic Disclaimer:</strong>

          This project was completed as part of the Regulatory Compliance
          Specialization offered by the University of Pennsylvania through
          Coursera. The company, scenarios, and risk assessments are fictional
          and created solely for educational and portfolio purposes.

        </p>

      </div>

    </div>
  </section>

</template>

<style scoped>
.landing-section {
  background-color: var(--color-primary);
  padding-top: 150px;
  padding-bottom: 80px;
}

.landing-title {
  font-size: 2.8rem;
  font-weight: 800;
}

.landing-subtitle {
  font-size: 1.15rem;
  opacity: 0.9;
}

.section-heading {
  font-weight: 700;
}

.blockquote-custom {
  font-style: italic;
}
</style>