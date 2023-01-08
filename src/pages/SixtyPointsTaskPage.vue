<template>
    <the-task-wrapper :task-file-name="taskFileName" :report-file-name="reportFileName">
        <h1 class="text-center mb-5">Завдання на 60 балів</h1>
        <base-collapsible>
            
        </base-collapsible>
    </the-task-wrapper>
</template>


<script>

import TheTaskWrapper from '../components/layout/TheTaskWrapper.vue';

export default {
    components: { TheTaskWrapper },
    data() {
        return {
            taskFileName: 'seminar1.pdf',
            reportFileName: 'seminar1Report.pdf'
        }
    }
}

</script>


<style scoped>
h1 {
    color: #1c1d1f;
    font-weight: 200;
}
</style>