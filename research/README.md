# ARG25 Project Submission Template

Welcome to Invisible Garden- ARG25.

Each participant or team will maintain this README throughout the program.  
You’ll update your progress weekly **in the same PR**, so mentors and reviewers can track your journey end-to-end.



##  Project Title
Fully Verifiable Autonomous Agents

![frog](frog_03.png "Frog")

*Verified gan generation onchian*
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
Significant optimizations for 32x32 pixel ouput GAN after many tests

Built classifier to recognize image class

Built composite proof system of GAN generation + image classifier

Can make and verify proof: This image model generate an image of type [class]

Failed to make final composite classifier proof 

## Final Wrap-Up
_After Week 3, summarize your final state: deliverables, repo links, and outcomes._

- **Main Repository Link:**  
https://github.com/LPSCRYPT/proof_chain
- **Demo / Deployment Link (if any):**  
- **Slides / Presentation (if any):**


## 🧾 Learnings
I learned a significant amount about the nuances of building ml models to be workable in zk circuits. There are many operations that balloon verifier memory usage, and in my first few tries I got OOM with 1TB of ram. After a number of optimizations, I was able to run the same model within 400 GB. To get models that are both quality in terms of inference and possible in terms of circuitization requires both deep knowledge of ai + zk fundamentals, as well as much trial and error.

There is very little information on this online, and even experts in this niche don't have the whole picture. Therefore, I believe that publishing a blog post with many of my findings can help other developers who are interested in development of zkml systems but don't have many resources to help them.

However, I did prove to myself that it is possible to fit a 32x32 (and likely larger) GAN inference on-chain, which I believe can be the driver for many more interesting projects in the future.

Even though we cannot fit any decent LLMs in a circuit currently, I believe that a clever combination of other models can create a somewhat agentic crowd-influenced system that, most importantly, has no single point of failure.


## Next Steps
I plan to keep developing this idea out until I can make a truly verifiable agent hyperstructure.

This will necesitate the deployment of many different verifier contracts to wire different model inferences together, as well as a sound socio-economic primitive to engage users to interact with the system. While there is still much to be done, I am much more confident in the basic fundamentals of zkml circuit proving to start thinking about these systems beyond the very low level mechanism implementations as I accomplished here. Botto, we're coming for you.

