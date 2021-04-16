<template>
  <div class="wrapper-small my-5">
    <div class="project-card md:flex mt-8">
      <div class="img max-w-lg md:max-w-sm  mx-auto">
        <img src="~/assets/fig/rcfr_horz.png" class="rounded-xl" alt="" />
      </div>
      <div class="flex flex-col justify-between max-w-lg mx-auto">
        <div class="txt md:px-5 lg:px-0">
          <h2 class="text-xl font-semibold text-gray-800">
            Multi-agent Reinforcement Learning in OpenSpiel
          </h2>

          <h3 class="text-sm lg:text-sm text-gray-500">
            Michael Walton, Viliam Lisy • 2021 arXiv
          </h3>
          <p class="text-base text-gray-700 my-3">
            In this report, we present results reproductions for several core
            algorithms implemented in the OpenSpiel framework for learning in
            games. The primary contribution of this work is a validation of
            OpenSpiel’s re-implemented search and Reinforcement Learning
            algorithms against the results reported in their respective
            originating works. Additionally, we provide complete documentation
            of hyperparameters and source code required to reproduce these
            experiments easily and exactly.
          </p>
        </div>
        <div>
          <div class="md:px-5 lg:px-0 py-3">
            <a
              href="https://arxiv.org/abs/2103.00187"
              target="_blank"
              class="bg-indigo-600 hover:bg-indigo-700 px-3 py-2 text-sm text-gray-200 font-semibold font-medium rounded-full"
              >Paper</a
            >
            <a
              href="https://github.com/aicenter/openspiel_reproductions"
              target="_blank"
              class="ml-6 text-indigo-600 hover:underline"
              >Code</a
            >
          </div>
        </div>
      </div>
    </div>
    <div class="project-card md:flex mt-16">
      <div class="img max-w-lg md:max-w-sm  mx-auto">
        <img src="~/assets/fig/hanabi_horz.png" class="rounded-xl" alt="" />
      </div>
      <div class="flex flex-col justify-between max-w-lg mx-auto">
        <div class="txt md:px-5 lg:px-0">
          <h2 class="text-xl font-semibold text-gray-800">
            Theory of Mind for Deep Reinforcement Learning in Hanabi
          </h2>
          <h3 class="text-sm lg:text-sm text-gray-500">
            Andrew Fuchs, Michael Walton, Theresa Chadwick, Doug Lange • 2019
            NeurIPS Deep Reinforcement Learning Workshop
          </h3>
          <p class="text-base text-gray-700 my-3">
            The partially observable card game Hanabi has recently been proposed
            as a new AI challenge problem due to its dependence on implicit
            communication conventions and apparent necessity of theory of mind
            reasoning for efficient play. In this work, we propose a mechanism
            for imbuing Reinforcement Learning agents with a theory of mind to
            discover efficient cooperative strategies in Hanabi. The primary
            contributions of this work are threefold: First, a formal definition
            of a computationally tractable mechanism for computing hand
            probabilities in Hanabi. Second, an extension to conventional Deep
            Reinforcement Learning that introduces reasoning over finitely
            nested theory of mind belief hierarchies. Finally, an intrinsic
            reward mechanism enabled by theory of mind that incentivizes agents
            to share strategically relevant private knowledge with their
            teammates. We demonstrate the utility of our algorithm against
            Rainbow, a state-of-the-art Reinforcement Learning agent.
          </p>
        </div>
        <div>
          <div class="md:px-5 lg:px-0 py-3">
            <a
              href="https://arxiv.org/abs/2101.09328"
              target="_blank"
              class="bg-indigo-600 hover:bg-indigo-700 px-3 py-2 text-sm text-gray-200 font-semibold rounded-full"
              >Paper</a
            >
            <a
              href="https://github.com/mwalton/ToM-hanabi-neurips19"
              target="_blank"
              class="ml-6 text-indigo-600 hover:underline"
              >Code</a
            >
          </div>
        </div>
      </div>
    </div>
    <div class="project-card md:flex mt-16">
      <div class="img max-w-lg md:max-w-sm  mx-auto">
        <img src="~/assets/fig/rf.png" class="rounded-xl" alt="" />
      </div>
      <div class="flex flex-col justify-between max-w-lg mx-auto">
        <div class="txt md:px-5 lg:px-0">
          <h2 class="text-xl font-semibold text-gray-800">
            Unsupervised Anomaly Detection for Digital Radio Frequency
            Transmissions
          </h2>
          <h3 class="text-sm lg:text-sm text-gray-500">
            Michael Walton, Maurice Ayache, Logan Straatemeier, Daniel Gebhardt,
            Benjamin Migliori • 2017 IEEE International Conference on Machine
            Learning and Applications
          </h3>
          <p class="text-base text-gray-700 my-3">
            We present a novel method of unsupervised anomaly detection using
            long-short-term memory mixture density networks (LSTM-MDN), applied
            to timeseries data of digital radio transmissions. The modern radio
            frequency (RF) environment is a dynamic and ever-changing complex
            milieu of signals, environmental effects, unintentional
            interference, and intentional jamming. A consequence of this complex
            mix is that RF receivers must become better and better at rejecting
            anomalous signals in order to recover the transmitted information.
            However, it is not always possible to know a priori what constitutes
            a valid signal and what constitutes an anomaly (intentional or
            otherwise), especially with the adoption of cognitive radio
            techniques. We show that an LSTM-MDN model is able to rapidly learn
            the training set and produce probability distribution functions for
            the expected signal as a function of time. We then demonstrate that
            the negative log likelihood of an incoming test transmission,
            conditioned on the training set, provides a metric that allows
            anomalous signals to be detected and labeled. We demonstrate this
            method for eight popular modulations and for three different anomaly
            types. By applying unsupervised learning in the temporal domain, we
            report a fully-generalizable anomaly detection method that may be
            applied to signals for which the transmission parameters may be
            unknown or obscured.
          </p>
        </div>
        <div>
          <div class="md:px-5 lg:px-0 py-3">
            <a
              href="https://ieeexplore.ieee.org/abstract/document/8260738"
              target="_blank"
              class="bg-indigo-600 hover:bg-indigo-700 px-3 py-2 text-sm text-gray-200 font-semibold rounded-full"
              >Paper</a
            >
          </div>
        </div>
      </div>
    </div>
    <div class="project-card md:flex mt-16">
      <div class="img max-w-lg md:max-w-sm  mx-auto">
        <img src="~/assets/fig/mlo.png" class="rounded-xl" alt="" />
      </div>
      <div class="flex flex-col justify-between max-w-lg mx-auto">
        <div class="txt md:px-5 lg:px-0">
          <h2 class="text-xl font-semibold text-gray-800">
            Hunting for Naval Mines with Deep Neural Networks
          </h2>
          <h3 class="text-sm lg:text-sm text-gray-500">
            Daniel Gebhardt, Keyur Parikh, Iryna Dzieciuch, Michael Walton, Nhut
            Anh Vo Hoang • 2017 IEEE OCEANS
          </h3>
          <p class="text-base text-gray-700 my-3">
            Explosive naval mines pose a threat to ocean and sea faring vessels,
            both military and civilian. This work applies deep neural network
            (DNN) methods to the problem of detecting minelike objects (MLO) on
            the seafloor in side-scan sonar imagery. We explored how the DNN
            depth, memory requirements, calculation requirements, and training
            data distribution affect detection efficacy. A visualization
            technique (class activation map) was incorporated that aids a user
            in interpreting the model’s behavior. We found that modest DNN model
            sizes yielded better accuracy (98%) than very simple DNN models
            (93%) and a support vector machine (78%). The largest DNN models
            achieved less than 1% efficacy increase at a cost of a 17x increase
            of trainable parameter count and computation requirements. In
            contrast to DNNs popularized for many-class image recognition tasks,
            the models for this task require far fewer computational resources
            (0.3% of parameters), and are suitable for embedded use within an
            autonomous unmanned underwater vehicle.
          </p>
        </div>
        <div>
          <div class="md:px-5 lg:px-0 py-3">
            <a
              href="https://ieeexplore.ieee.org/abstract/document/8232216"
              target="_blank"
              class="bg-indigo-600 hover:bg-indigo-700 px-3 py-2 text-sm text-gray-200 font-semibold rounded-full"
              >Paper</a
            >
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
  export default {};
</script>

<style></style>
