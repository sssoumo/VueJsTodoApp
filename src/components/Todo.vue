<template>
<div style="max-height: 97.5vh; height: 100%">
<v-container fluid fill-height pl-auto pr-0 pb-0 pt-0>
        <v-layout row>
            <v-flex lg3 pr-2>
                <Lists/>
            </v-flex>
            <v-flex lg6 pr-2 pl-2>
                Tasks
            </v-flex>
            <v-flex lg3 pl2>
                Options
            </v-flex>
        </v-layout>
    </v-container>
    <v-footer height="auto" color="indigo">
        <v-layout justify-center>
            <v-flex indigo white--text text-xs-center>
                &copy;2019
                <strong>Saadman Soumique</strong>
            </v-flex>
        </v-layout>
    </v-footer>
</div>
</template>

<script>
import Lists from "./Lists";
export default {
    name: "todo",
    components: { Lists }
}
</script>>