<template>
  <v-table height="300px" fixed-header>
    <thead>
      <tr>
        <th class="text-left">Timeline</th>
        <th class="text-left">Date</th>
      </tr>
    </thead>
    <tbody>
      <tr v-for="item in timelines" :key="item.name">
        <td>{{ item.name }}</td>
        <td>{{ item.date }}</td>
      </tr>
    </tbody>
  </v-table>
</template>

<script>
  export default {
    data() {
      return {
        timelines: [
          {
            name: 'Fitness Milestones',
            date: 'April 1, 1995 ',
          },
          {
            name: 'Family Adventures',
            date: 'December 25, 1997 ',
          },
          {
            name: 'Wedding Planning Story',
            date: 'October 10, 1999 ',
          },
          {
            name: 'Startup Growth Journey',
            date: 'February 14, 2010 ',
          },
          {
            name: 'Journey to Self-Discovery',
            date: 'March 12, 2010 ',
          },
          {
            name: 'Relationship Highlights',
            date: 'February 23, 2014 ',
          },
          {
            name: 'Tech Innovations Over Time',
            date: 'April 13, 2018 ',
          },
          {
            name: 'Our Home Renovation Journey',
            date: 'October 17, 2020 ',
          },
          {
            name: 'Steps to Graduation',
            date: 'June 2, 2023 ',
          },
          {
            name: 'My Learning Path',
            date: 'April 1, 2024 ',
          },
        ],
      }
    },
  }
</script>
