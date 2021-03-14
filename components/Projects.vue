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
  </div>
</template>

<script>
export default {};
</script>

<style></style>
