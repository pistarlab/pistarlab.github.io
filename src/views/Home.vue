<template>
<div>
    <b-jumbotron class="bam" text-variant="white" border-variant="light">
        <template #header>Build. Play. Learn.</template>

        <template #lead>
            Learn about AI by creating your own.
        </template>

        <b-container fluid>
            <b-row>
                <b-col>
                    <p>
                        An <b>open source</b> AI experimentation platform focused on making development easy and fun.
                    </p>
                    <ul>
                        <li>
                            Intuitive UI for creating and train agents
                        </li>
                        <li>
                            Growing selection of agent algorithms and environments.
                        </li>
                        <li>
                            Simple plugin system for adding new algorithms and environments.
                        </li>
                        <li>
                            Python API to solve more complicated tasks.
                        </li>
                        <li>
                            Competitions and Multi Agents Matches (Coming soon)
                        </li>
                        <li>
                            Learning resources (Coming soon)
                        </li>
                    </ul>
                </b-col>
                <b-col class="text-center">
                    <img height="200px" src="@/assets/robot.png" />
                </b-col>
            </b-row>
        </b-container>

    </b-jumbotron>
    <div class="mt-5 mb-5">
    </div>
    <b-container fluid>
        <b-row>
            <b-col class="text-center">
                <b-button variant="primary" href="https://pistarlab.readthedocs.io/en/latest/installation.html" size="lg"> Install </b-button> (WARNING: This is not ready for general use. Still in early development)
            </b-col>

        </b-row>
        <div class="mt-4 mb-4">
            <hr />
        </div>

        <b-row>
            <b-col class="my-auto text-right mr-5">
                <h4>Train your agents on a growing selection environments.</h4>
                
            </b-col>
            <b-col class="text-left">
 <img style="width:500px" src="@/assets/pistarlab_envs.png" />
             
            </b-col>
        </b-row>
        <div class="mt-4 mb-4">
            <hr />
        </div>

        <b-row>

            <b-col class="text-right">

                  <img style="width:500px" src="@/assets/pistarlab_agent_home.png" />
            </b-col>
            <b-col class="my-auto text-left ml-5">
                <h4>Use an existing agent algorithm or bring your own.</h4>
            </b-col>
        </b-row>
        <div class="mt-4 mb-4">
            <hr />
        </div>

        <b-row>
            <b-col class="my-auto text-right mr-5">
                <h4>Watch your agents learn in real-time.</h4>
            </b-col>

            <b-col class="text-left">

                <img style="width:500px" src="@/assets/pistarlab_session_stats.png" />
            </b-col>
        </b-row>
    </b-container>
</div>
</template>

<script>
export default {
    name: 'Home',
    components: {}
}
</script>
