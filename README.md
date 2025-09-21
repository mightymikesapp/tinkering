# Remedeez UCC Remedies Lab

Remedeez is a single-page web application that functions as a "UCC Remedies Lab." It's a calculator designed to help users understand and compare different damage remedies available to buyers and sellers for breach of contract under the Uniform Commercial Code (UCC), primarily Article 2 (Sales).

This tool is ideal for law students studying contracts or commercial law, as well as legal professionals who need a quick way to calculate and visualize potential outcomes in a contract dispute.

## Features

- **Comprehensive Remedy Calculation:** Calculates damages for both buyers (seller's breach) and sellers (buyer's breach) based on various UCC sections.
- **Side-by-Side Comparison:** Displays all relevant remedies in parallel, allowing users to easily compare the outcomes of different legal theories (e.g., Cover vs. Market Damages).
- **Interactive Charts:** Visualizes the calculated remedy amounts in bar charts, highlighting the most favorable option.
- **Scenario Lab:** Comes pre-loaded with scenarios from well-known legal cases and hypotheticals to demonstrate how the calculations apply to real-world facts.
- **Final Judgment Synthesis:** For cases involving a buyer's deposit, the tool calculates the final payment owed by one party to the other after offsetting the seller's damages against the deposit.
- **Detailed Breakdowns:** Each calculation shows the formula used and a breakdown of the components (e.g., Contract Price, Market Price, Incidental Damages).
- **Built-in Guidance:** Includes tooltips and helper text to explain key legal concepts and the prerequisites for each type of remedy.

## How to Use

1.  Download the `remedeez calculator v.o1.html` file.
2.  Open the file in any modern web browser (like Chrome, Firefox, Safari, or Edge).
3.  No internet connection or installation is required.

Once opened, you can either input your own numbers into the fact pattern fields or select a pre-loaded case from the "Scenario Lab" dropdown to get started. Click the "Calculate & Compare Remedies" button to see the results.

## Scenarios Included

The Scenario Lab includes the following cases and hypotheticals:

- **Neri v. Retail Marine Corp. (NY 1972):** A classic case illustrating lost-volume seller profits under §2-708(2).
- **Pollack v. Crocker (S.D.N.Y. 1987):** Demonstrates an action for the price under §2-709 for accepted goods.
- **Chicago Roller Skate Mfg. v. Sokol Mfg. (Neb. 1970):** Shows the interplay between resale damages (§2-706) and market damages (§2-708(1)).
- **Egerer v. CSR West (Wash. Ct. App. 2003):** A buyer's remedy case involving cover (§2-712) and market damages (§2-713).
- **Hypo: Accepted Goods with Warranty Breach:** A hypothetical for calculating breach of warranty damages under §2-714.
- **Hypo: Large Deposit, Quick Resale:** A scenario testing the limits on a seller's retention of a breaching buyer's deposit under §2-718.
- **Hypo: Unique Artwork, Buyer Seeks SP:** A situation designed to prompt discussion of specific performance (§2-716) versus monetary damages.

## Technical Details

- **Frontend:** Built with vanilla HTML, CSS, and JavaScript.
- **Dependencies:** None. The entire application is self-contained in a single `.html` file.
