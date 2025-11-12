# ARG25 Project Submission Template

Welcome to Invisible Garden- ARG25.

Each participant or team will maintain this README throughout the program.  
You’ll update your progress weekly **in the same PR**, so mentors and reviewers can track your journey end-to-end.



##  Project Title
Fully Verifiable Autonomous Agents

## Team
- Team/Individual Name:Moist Cryptography Research Unit
- GitHub Handles: @lpscrypt
- Devfolio Handles: memec

## Project Description
Many companies claim to be pioneering the creation of autonomous agents via web3AI systems. These systems, however, invariably are built as a trusted bridge for sending inference to chain. The risk factors of these trusted bridges greatly reduces the capital which such systems can be trusted to bear. Similarly, the idea of 'autonomous agents' has become decoupled from a core notion of autonomy - their complete reliance on trusted human actors. This is evident in the system Botto, which claims to be a fully autonomous onchain artist, however relies on the human creator, Mario Klingeman, to perform all inference correctly and ferry it to chain. While this may work in very small scale systems where the trust assumption is valid, such systems by their very nature cannot scale to be [hyperstructures](https://jacob.energy/hyperstructures.html). 

The Moist Cryptography Research Unit seeks to explore the opposite end of the pole - exactly how far can we currently get in developing **verifiable agents**, where the trust assumption of inference bridging is solved with proofs of inference that can be consumed in a smart co*ntract. The compute overhead of prooving inference on a machine learning model are currently very large - therefore, we must design systems that can work within the current technology paradigm of zero-knowledge machine learning (ZKML). This restricts us to very small models that need to be optimized for zero-knowledge circuit building. 

Our question, then, is what are the types of verified agent systems which we can build today that, through following the design principles of hyperstructures, might exist without a single human point of failure into the indefinite future?

## Tech Stack
EZKL, pytorch, foundry

## Objectives
1. Increase knowledge of ml model optimizations for zk circuits
2. Gain better understanding of what types of verified agent systems are currently achievable 
3. Build a Botto-like autonomous artist system, but as a fully **verifiable agent** system

## Weekly Progress

### Week 1 (ends Oct 31)
**Goals:**
Preliminary Research

**Progress Summary:** 
https://arxiv.org/pdf/2510.01967
https://arxiv.org/pdf/2508.06972
https://arxiv.org/pdf/2310.14848
https://arxiv.org/pdf/2210.08674
https://arxiv.org/pdf/2502.18535
https://arxiv.org/pdf/2409.12055
https://arxiv.org/pdf/1802.05957

### Week 2 (ends Nov 7)
**Goals:**  
Further research & synthesis
 
**Progress Summary:**
GAN optimizations:

Other model types:
1. Classifier
2. Policy
3. Anomaly Detection

### 🗓️ Week 3 (ends Nov 14)
**Goals:**  
GAN tests & benchmarks
Building final system, deploy testnet & run tests

**Progress Summary:**  



## Final Wrap-Up
_After Week 3, summarize your final state: deliverables, repo links, and outcomes._

- **Main Repository Link:**  
- **Demo / Deployment Link (if any):**  
- **Slides / Presentation (if any):**



## 🧾 Learnings
_What did you learn or improve during ARG25?_



## Next Steps
_If you plan to continue development beyond ARG25, what’s next?_



_This template is part of the [ARG25 Projects Repository](https://github.com/invisible-garden/arg25-projects)._  
_Update this file weekly by committing and pushing to your fork, then raising a PR at the end of each week._
