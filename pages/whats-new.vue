<script>
export default {
  head () {
    return {
      title: 'What\'s New',
      meta: [{
        hid: 'description',
        name: 'description',
        content: 'Ambulance Medical Service is committed to continuously upgrading our equipment to serve our patients better in emergencies. See our latest updates here!'
      }],
      link: [
        {
          rel: 'canonical',
          href: process.env.baseUrl + this.$route.path + '/'
        }
      ]
    }
  }
}
</script>

<template>
<default-page>
  <h1 id="page_title">What's New</h1>
  <h3>April 2020</h3>
  <p>
    As of April 2020, we have expanded our fleet to 39 ambulances!
  </p>
  <p>
    We are proud to support COVID-19 since February 2020 and have dedicated a section of our fleet to support 993 transport services of suspect and confirmed cases. Rest assured that to avoid cross-infectivity with our regular patients, the COVID team is separate from our regular teams. Our COVID crew is well trained and adheres to strict personal-protection and sanitisation protocol. Preventive measures have also been ramped up for all regular cases.
  </p>
  <p>
    Under new MOH regulations for improving stricter standards for private ambulances, AMS has been accredited for both Emergency Ambulance Services (EAS) and Medical Transport Services (MTS). With our commitment to maintaining professional services and top-line equipment, we are one of the earliest private ambulances to pass accreditation standards!
  </p>

  <h3>November 2019</h3>
  <p>
    We have received ISO 9001 : 2015 from November 2019. It is awarded to companies that meet requirements for a quality management system that consistently meet high standards of service and customer satisfaction. See more details at https://www.iso.org/standard/62085.html
  </p>
  <p>
    We have also been promoted from BizSafe Level 3 to BizSafe Level 4!
  </p>

  <div slot="sidebar">
    <enquiry-box/>
    <address-area />
    <facebook-widget />
  </div>
</default-page>
</template>


<style lang="scss" scoped>
.page_title {
  font-family: Calibri,sans-serif;
  color: #7c257a;
  font-size: 32px;
  margin: 0 0 20px;
  text-align: left;
  text-transform: capitalize;
  width: 100%;
}
</style>