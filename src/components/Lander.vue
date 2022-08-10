<template>
    <div>
        <!-- lander section -->
        <section class="section">
            <div class="container-fliud">
                <img alt="Vue logo" class="rounded-circle" src="https://i.ibb.co/8KGDVwr/136701.jpg">
                <h1>Quazi Rubayat Hassan</h1>
                <h2>Email: rubayat.roktim@gmail.com</h2>
                <h3>Mob: 01675577549</h3>

                <h1>Full Stack Web Developer</h1>

                <p>Achieving an interesting and challenging job, where I can utilize my degree in CSE, knowledge gained
                    in previous
                    academic courses, my interpersonal and technical skills in order to develop my career as well as to
                    contribute in the
                    welfare of the organization by dedication, hard work and passion.</p>
                <button type="button" class="btn btn-primary btn-lg" data-toggle="modal"
                    data-target=".bd-example-modal-lg">Contact</button>

            </div>
        </section>
        

        <section class="section1">
            <div>
                <b-card no-body class="overflow-hidden" style="max-width: 540px;">
                    <b-row no-gutters>
                        <b-col md="6">
                            <b-card-img src="https://picsum.photos/400/400/?image=20" alt="Image" class="rounded-0">
                            </b-card-img>
                        </b-col>
                        <b-col md="6">
                            <b-card-body title="Horizontal Card">
                                <b-card-text>
                                    <h1>PROFESSIONAL SOFTWARE SKILLS </h1></b-card-text>

                                <h2>
                                    React, JavaScript,Vue, Node.js, Node express, MongoDB, HTML, CSS, Bootstrap, Tailwind, my sql, Figma, Firebase, ReactDom, React Query, React Router, React Hooks, etc.</h2>
                            </b-card-body>
                        </b-col>
                    </b-row>
                </b-card>
            </div>
        </section>

        <!-- portfolio section -->
        <section class="protfolio">
            <h1>Some Project</h1>
            <p>These are suppose to be sample projects link</p>
            <div class="container">
                <div class="row">

                    <div class="col-md-4">
                        <div class="card">
                            <div class="card-head">
                                <img alt="Vue logo" class="rounded-circle img-custome"
                                    src="https://www.nopio.com/wp-content/uploads/2016/05/web-development.jpg">
                                <h2>Doctor Portal</h2>
                            </div>
                            <hr>
                            <div class="card-body">
                                <p>
                                    • Doctors’ information and Appointment<br>
                                    • Treatment <br>
                                    • Booking And Payment
                                </p>

                                <ul>
                                    <li><a href="https://doctors-portal-cc047.web.app/" target="_blank"
                                            rel="noopener">Live-site</a></li>
                                    <li><a href="https://github.com/RubayatHassan/Doctors-Website" target="_blank"
                                            rel="noopener">Clint-site</a></li>
                                    <li><a href="https://github.com/RubayatHassan/Doctors-portal-server" target="_blank"
                                            rel="noopener">Server-site</a></li>

                                </ul>
                            </div>
                        </div>
                        <br>
                    </div>

                    <div class="col-md-4">
                        <div class="card">
                            <div class="card-head">
                                <img alt="Vue logo" class="rounded-circle img-custome"
                                    src="https://i.pinimg.com/originals/4a/70/56/4a70563234301578c158dc142384a1c3.png">
                                <h2>Warehouse Managment</h2>
                            </div>
                            <hr>
                            <div class="card-body">
                                <p>
                                    •Warehouse Mmanagement<br>
                                    •Order Items<br>
                                    •Confram Order

                                </p>
                                <ul>
                                    <li><a href="https://wearhouse-63077.web.app/home" target="_blank"
                                            rel="noopener">Live-site</a></li>
                                    <li><a href="https://github.com/ProgrammingHeroWC4/warehouse-management-client-side-RubayatHassan" target="_blank"
                                            rel="noopener">Clint-site</a></li>
                                    <li><a href="https://github.com/ProgrammingHeroWC4/warehouse-management-server-side-RubayatHassan" target="_blank" rel="noopener">Server-site</a></li>

                                </ul>

                            </div>
                        </div>
                        <br>
                    </div>

                    <div class="col-md-4">
                        <div class="card">
                            <div class="card-head">
                                <img alt="Vue logo" class="rounded-circle img-custome"
                                    src="https://cdn.mos.cms.futurecdn.net/wH5y2PkWhCxqKBje8rBp5e.jpg">
                                <h2>Tourist Guider</h2>
                            </div>
                            <hr>
                            <div class="card-body">
                                <p>
                                    • Tourist Guideline<br>
                                    • Tourist Place view<br>
                                    • Place Knowladge
                                </p>
                                <ul>
                                    <li><a href="https://shiny-kitten-120978.netlify.app/" target="_blank"
                                            rel="noopener">Live-site</a></li>
                                    <li><a href="https://github.com/RubayatHassan/Tourist-Site_client" target="_blank"
                                            rel="noopener">Clint-site</a></li>
                                    <li><a href="" target="_blank" rel="noopener">Server-site</a></li>
                                </ul>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- modal for contact -->

        <section class="">
            <div class="modal fade bd-example-modal-lg" tabindex="-1" role="dialog" aria-labelledby="myLargeModalLabel"
                aria-hidden="true">
                <div class="modal-dialog modal-lg">
                    <div class="modal-content">
                        <talk />
                    </div>
                </div>
            </div>
        </section>

    </div>
</template>

<script lang="ts">
import talk from './Contact.vue'
export default {
    name: 'Lander',
    components: {
        talk
    }
}
</script>

<style lang="css" scoped>
.section {
    padding-top: 10%;
    padding-bottom: 10%;
}
.section1 {
    padding-top: 3%;
    padding-bottom: 3%;
}

.protfolio {
    background-color: #34345238;
    padding-top: 8%;
    padding-bottom: 14%;
    /* padding:15% */
}

.img-custome {
    width: 140px;
    height: 140px;
    margin-top: 15px;
}
</style>