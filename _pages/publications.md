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
              <paper>Hierarchical Universal Value Functional Approximators</paper>
              <br>
              <b>Rushiv Arora</b>, Ignacio Gavier, Eliot Moss
              <br>
              Pre-print
              <br>
              <details>
                <summary>Abstract  </summary>            
                  <p class="message">
                  <br><br>
                  <b>Keywords</b>: Reinforcement Learning, Machine Learning
                  </p>
              </details>
          </p>  
     </td>
   </tr>

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
              Submitted to NeurIPS 2023
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
              Submitted to IEEE Transactions on Automation Science and Engineering
             <br>
             <a href="https://arxiv.org/abs/2211.15866">arXiv</a>
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
