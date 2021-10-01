<template>
  <div>
    <h1>Event List</h1>
    <event-card />
  </div>
</template>
<script>
import EventCard from '@/components/EventCard.vue';
export default {
  name: 'EventList',
  components: {
    EventCard
  }
};
</script>
