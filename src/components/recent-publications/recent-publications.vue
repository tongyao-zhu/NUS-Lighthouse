<template src="./recent-publications.html"></template>
<style src="./recent-publications.scss" lang="scss"></style>
<script>

import eachPublication from './each-publication';


export default {
  name: 'RecentPublications',
  components: {
    eachPublication,
  },

  data() {
    return {
      publications: [
        'Kang, K., Hahn, J. and De, P. (2017) "Learning Effects of Domain, Technology, and Customer Knowledge in Information Systems Development: An Empirical Study, " Information Systems Research, 28(4), pp. 797-811. DOI:10.1287/isre.2017.0713.',
        'Moon, J.Y., Hahn, J., Oh, W. and Kim, T. (2016) "Leader Influence on Sustained Participation in Online Collaborative Work Communities: A Simulation - based Approach, " Information Systems Research, 27(2), pp. 383-402. (DOI:10.1287/isre.2016.0632)',
        'Kankanhalli, A., Hahn, J., Tan, S. and Gao, G. (2016) "Big Data and Analytics in Healthcare: Introduction to the Special Issue, " Information Systems Frontiers, 18(2) Special Section on Big Data and Analytics in Healthcare, pp. 233-235. (DOI: 10.1007/s10796-016-9641-2) [Guest Editorial]',
      ],
    };
  },
};

</script>
