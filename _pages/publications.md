---
permalink: "/publication/"
layout: page
title: Publications
sidebar_link: true
order: 2
---


<style>

table {
  margin-bottom: 1rem;
  width: 100%;
  font-size: 85%;
  border: 0px solid $border-color;
  border-collapse: collapse;
}

td,
th {
  padding:  1rem .25rem;
  border: 0px solid $border-color;
}

th {
  text-align: left;
}

tbody tr:nth-child(odd) td,
tbody tr:nth-child(odd) th {
  background-color: transparent;
}

paper {
 color: #;
 font-weight:bold;
}


</style>
#### Working Papers/Preprints

<table width="100%" align="center" border="0" cellspacing="0" cellpadding="20">

   <tr>
     <td width="20%"  valign="middle">
     </td>
     <td valign="top" width="80%">
          <p>
              <paper>DIY Mujoco: Building and Testing Physical Robots for RL Generalization</paper>
              <br>
              <b>Rushiv Arora</b>
              <br>
              Pre-print
              <br>
              <details>
                <summary>Abstract  </summary>            
                  <p class="message">
                  The Mujoco Environment is widely used in Reinforcement Learning as a measure of performance in Robotics domains. This is often a crude approximation of the generalization of performance to real-robots. We exploit the fact that these robots rely on small degrees-of-freedom to create physical robots using commonly available parts and processes that can be easily recreated by researchers who wish to test the generalization of their algorithms in the real-world. By doing so, we aim to increase access of robotic domains to researchers and bolster the claims of Sim2Real methods. We test our Mujoco robots by measuring generalization of policies learned via popular algorithms, namely Soft-Actor Critic and Proximal Policy Optimization, to the physical robot.
                  <br><br>
                  <b>Keywords</b>: Reinforcement Learning, Machine Learning, Robotics, Sim2Real
                  </p>
              </details>
          </p>  
     </td>
   </tr>

   <tr>
     <td width="20%"  valign="middle">
     </td>
     <td valign="top" width="80%">
          <p>
              <paper>Options for Multi-Task RL</paper>
              <br>
              <b>Rushiv Arora</b>, Aline Weber, Bruno Castro da Silva
              <br>
              Pre-print
              <br>
              <details>
                <summary>Abstract  </summary>            
                  <p class="message">
                  <br><br>
                  <b>Keywords</b>: Hierarchical Reinforcement Learning, Machine Learning
                  </p>
              </details>
          </p>  
     </td>
   </tr>
  </table>

#### 2024

<table width="100%" align="center" border="0" cellspacing="0" cellpadding="20">

  <tr>
     <td width="20%"  valign="middle">
     </td>
     <td valign="top" width="80%">
          <p>
              <paper>Hierarchical Universal Value Functional Approximators</paper>
              <br>
              <b>Rushiv Arora</b>
              <br>
              Under Review
              <br>
              <details>
                <summary>Abstract  <a href="https://arxiv.org/abs/2410.08997">arXiv</a> </summary>   </summary>            
                  <p class="message">
                  There have been key advancements to building universal approximators for multi-goal collections of reinforcement learning value functions---key elements in estimating long-term returns of states in a parameterized manner. We extend this to hierarchical reinforcement learning, using the options framework, by introducing hierarchical universal value function approximators (H-UVFAs). This allows us to leverage the added benefits of scaling, planning, and generalization expected in temporal abstraction settings. We develop supervised and reinforcement learning methods for learning embeddings of the states, goals, options, and actions in the two hierarchical value functions: $Q(s, g, o; \theta)$ and $Q(s, g, o, a; \theta)$. Finally we demonstrate generalization of the HUVFAs and show they outperform corresponding UVFAs.
                  <br><br>
                  <b>Keywords</b>: Reinforcement Learning, Universal Value Function Approximators, Hierarchical Reinforcement Learning
                  </p>
              </details>
          </p>  
     </td>
   </tr>

   <tr>
     <td width="20%"  valign="middle">
     </td>
     <td valign="top" width="80%">
          <p>
              <paper>Locally Constrained Representations in Reinforcement Learning</paper>
              <br>
              Somjith Nath, <b>Rushiv Arora</b>, Samira Ebrahimi Kahou
              <br>
              Under review
              <br>
              <details>
                <summary>Abstract  </summary>            
                  <p class="message">
                  The success of Reinforcement Learning (RL) heavily relies on the ability to learn robust representations from the observations of the environment. In most cases, the representations learned purely by the reinforcement learning loss can differ vastly across states depending on how the value functions change. However, the representations learned need not be very specific to the task at hand. Relying only on the Reinforcement Learning objective may yield representations that vary greatly across successive time steps. In addition, since the Reinforcement Learning loss has a changing target, the representations learned would depend on how good the current values/policies are. Thus, disentangling the representations from the main task would allow them to focus not only on the task-specific features but also the environment dynamics. To this end, we propose locally constrained representations, where an auxiliary loss forces the state representations to be predictable by the representations of the neighboring states. This encourages the representations to be driven not only by the value/policy learning but an additional loss that constrains the representations from over-fitting to the value loss. We evaluate the proposed method on several known benchmarks and observe strong performance. Especially in continuous control tasks, our experiments show a significant performance improvement.
                  <br><br>
                  <b>Keywords</b>: Reinforcement Learning, Machine Learning
                  </p>
              </details>
          </p>  
     </td>
   </tr>

  </table>

#### 2023

<table width="100%" align="center" border="0" cellspacing="0" cellpadding="20">
  <tr>
     <td width="20%"  valign="middle">
           <img src="/images/publications/TFA2022.png" alt="TFA" style="vertical-align:middle; width: 80%; margin:0px 10px; border-radius:0%"/>
     </td>
     <td valign="top" width="80%">
          <p>
              <paper>On the Dynamics of Learning Time-Aware Behavior with Recurrent Neural Networks</paper>
              <br>
              Peter Delmastro, <b>Rushiv Arora</b>, Edward Rietman, Hava Siegelmann
              <br>
              Under Review
              <br>
              <details>
                <summary>Abstract  | <a href="https://arxiv.org/abs/2306.07125">arXiv</a> </summary>            
                  <p class="message">
                  Recurrent Neural Networks (RNNs) have shown great success in modeling time-dependent patterns, but there is limited research on their learned representations of latent temporal features and the emergence of these representations during training. To address this gap, we use timed automata (TA) to introduce a family of tasks modeling behavior dependent on hidden temporal variables whose complexity is directly controllable. Building upon past studies from the perspective of dynamical systems, we train RNNs to emulate temporal flipflops, a new collection of TA that emphasizes the need for time-awareness over long-term memory. We find that these RNNs learn in phases - they quickly perfect any time-independent behavior, but they initially struggle to discover the hidden time-dependence. In the case of periodic "time-of-day" aware automata, we show that the RNNs learn to switch between periodic orbits that encode time modulo the period of the transition rules. We subsequently apply fixed point stability analysis to monitor changes in the RNN dynamics during training, and we observe that the learning phases are separated by a bifurcation from which the periodic behavior emerges. In this way, we demonstrate how dynamical systems theory can provide insights into not only the learned representations of these models, but also the dynamics of the learning process itself. We argue that this style of analysis may also be applicable to understanding training pathologies of recurrent architectures in contexts outside of time-awareness.
                  <br><br>
                  <b>Keywords</b>: Neural Networks/Deep Learning, Computational complexity, Learning from complex/structured data, Dynamical systems theory
                  </p>
              </details>
          </p>  
     </td>
   </tr>

   <tr>
      <td width="20%"  valign="middle">
             <img src="/images/publications/UAV2022TVT.png" alt="UAV" style="vertical-align:middle; width: 80%; margin:0px 10px; border-radius:0%"/>
      </td>
      <td valign="top" width="80%">
           <p>
               <paper>A Search and Detection UAV System: from Design to Implementation</paper>
               <br>
               <a href='/publications'>Mohammadjavad Khosravi</a>,
               <b>Rushiv Arora</b>,  
               <a href='https://scholar.google.com/citations?user=jO4Xj9oAAAAJ&hl=en'>Saeede Enayati</a>,
               <a href='https://scholar.google.com/citations?user=2OCQ9GkAAAAJ&hl=en'>Hossein Pishro-Nik</a>,
               <br>
              Accepted at IEEE Transactions on Automation Science and Engineering
             <br>
             <a href="https://arxiv.org/abs/2211.15866">arXiv</a>
           </p>  
      </td>
    </tr>

  <tr>
      <td width="20%"  valign="middle">
             <img src="/images/publications/UAV2022TVT.png" alt="UAV" style="vertical-align:middle; width: 80%; margin:0px 10px; border-radius:0%"/>
      </td>
      <td valign="top" width="80%">
           <p>
               <paper>Deployment of a UAV-Based Fire Detection System</paper>
               <br>
               <b>Rushiv Arora</b>, 
               <a href='/publications'>Mohammadjavad Khosravi</a>, 
               <a href='https://scholar.google.com/citations?user=jO4Xj9oAAAAJ&hl=en'>Saeede Enayati</a>,
               <a href='https://scholar.google.com/citations?user=2OCQ9GkAAAAJ&hl=en'>Hossein Pishro-Nik</a>,
               <br>
              2023 IEEE 97th Vehicular Technology Conference (VTC2023-Spring)
             <br>
             <a href="https://ieeexplore.ieee.org/abstract/document/10200883">IEEE Xplore</a>
           </p>  
      </td>
    </tr>

</table>


#### 2022

<table width="100%" align="center" border="0" cellspacing="0" cellpadding="20">

  <tr>
     <td width="20%"  valign="middle">
            <img src="/images/publications/DARL2022SINDy.png" alt="SINDy" style="vertical-align:middle; width: 80%; margin:0px 10px; border-radius:0%"/>
     </td>
     <td valign="top" width="80%">
          <p>
              <paper>Model-Based Reinforcement Learning with SINDy</paper>
              <br>
              <b>Rushiv Arora</b>,  
              <a href='https://people.cs.umass.edu/~moss/?_gl=1*sdbxyt*_ga*MTY0NTE1MTIxNS4xNTM2NTI5Mzg0*_ga_21RLS0L7EB*MTY1NzQzODA5MC4zNTIuMS4xNjU3NDM4MTMxLjA.&_ga=2.225631898.1219407999.1657438091-1645151215.1536529384'>Eliot Moss</a>,
              <a href='https://people.cs.umass.edu/~bsilva/'>Bruno Castro da Silva</a>,
              <br>
             DARL Workshop @ The Thirty-ninth International Conference on Machine Learning (ICML 2022)
             <br>
             <p style="color:red">(Representative Technical Writing)</p>
              <details>
                <summary>Abstract  | <a href="https://openreview.net/forum?id=3xBZY7LGorK&referrer=%5BAuthor%20Console%5D(%2Fgroup%3Fid%3DICML.cc%2F2022%2FWorkshop%2FDARL%2FAuthors%23your-submissions)">Paper</a> | <a href="https://arxiv.org/abs/2208.14501">arXiv</a> | </summary>            
                  <p class="message">
                  We draw on the latest advancements in the physics community to propose a novel method for discovering the governing non-linear dynamics of physical systems in reinforcement learning (RL).  We establish that this method is capable of discovering the underlying dynamics using significantly fewer trajectories (as little as one rollout with ≤ 30 time steps) than state of the art model learning algorithms.  Further, the technique learns a model that is accurate enough to induce near-optimal policies given significantly fewer trajectories than those required by model-free algorithms.  It brings the benefits of model-based RL without requiring a model to be developed in advance, for systems that have physics-based dynamics.
                  <br><br>
                  To establish the validity and applicability of this algorithm, we conduct experiments on four classic control tasks.  We found that an optimal policy trained on the discovered dynamics of the underlying system can generalize well.  Further, the learned policy performs well when deployed on the actual physical system, thus bridging the model to real system gap.  We further compare our method to state-of-the-art model-based and model-free approaches, and show that our method requires fewer trajectories sampled on the true physical system compared other methods.  Additionally, we explored approximate dynamics models and found that they also can perform well.
                  <br><br>
                  <b>Keywords</b>: model-based Reinforcement Learning, model learning, non-linear dynamical systems
                  </p>
              </details>
          </p>  
     </td>
   </tr>



</table>
