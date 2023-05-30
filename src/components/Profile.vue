<template>
    <div class="container">
        <div class="row pt-4 pb-2 justify-content-center sticky-top">
            <div class="col-8 text-center font-monospace">
                <div id="list-example" class="list-group list-group-horizontal shadow-sm">
                <a class="list-group-item list-group-item-action" href="#i1">Personal Info</a>
                <a class="list-group-item list-group-item-action" href="#i2">Professional Info</a>
                <a class="list-group-item list-group-item-action" href="#i3">Family Info</a>
                </div>
            </div>
        </div>
        <hr class="border border-info border-1 opacity-25">
        
        <p class="h5 pt-3 text-center">Daniel Wheatley</p>
        <div data-bs-spy="scroll" data-bs-target="#list-example" data-bs-smooth-scroll="true" class="scrollspy-example">
            <div class="row p-4 ">
                <div class="col">
                    <img src="../../src/assets/1.jpg" class="img-fluid" alt="...">
                </div>
                <div class="col">
                    <img src="../../src/assets/2.webp" class="img-fluid" alt="...">
                </div>
                <div class="col">
                    <img src="../../src/assets/3.webp" class="img-fluid" alt="...">
                </div>
                <div class="col">
                    <img src="../../src/assets/4.webp" class="img-fluid" alt="...">
                </div>
            </div>
        <hr class="border border-info border-1 opacity-25">
        
        <p id="i1" class="h5 m-4 text-center">Personal Information</p>
        <div class="row  font-monospace">
            <div class="col-2"></div>
            <div class="col">
                <table class="table">
                    <thead>
                        <tr>
                            <th scope="col"></th>
                            <th scope="col" class="w-75"></th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td class="fw-semibold p-3">Full Name:</td>
                            <td class="fw-normal p-3">Margot Foster</td>
                        </tr>
                        <tr>
                            <td class="fw-semibold p-3">Phone Number:</td>
                            <td class="fw-normal p-3">+91 7898556643</td>
                        </tr>
                        <tr>
                            <td class="fw-semibold p-3">Email ID:</td>
                            <td class="fw-normal p-3">Margotfoster@gmailcom</td>
                        </tr>
                        <tr>
                            <td class="fw-semibold p-3">Date of Birth</td>
                            <td class="fw-normal p-3">23 May 1995</td>
                        </tr>
                        <tr>
                            <td class="fw-semibold p-3">Time of Birth</td>
                            <td class="fw-normal p-3">4:30pm</td>
                        </tr>
                        <tr>
                            <td class="fw-semibold p-3">Place of Birth</td>
                            <td class="fw-semibld p-3">Hyderabad, India</td>
                        </tr>
                        <tr>
                            <td class="fw-semibold p-3">Gothram</td>
                            <td class="fw-normal p-3">gothram</td>
                        </tr>
                        <tr>
                            <td class="fw-semibold p-3">Birth Star</td>
                            <td class="fw-normal p-3">starname</td>
                        </tr>
                        <tr>
                            <td class="fw-semibold p-3">Rasi/Zodiac Sign</td>
                            <td class="fw-normal p-3">Aquarius</td>
                        </tr>
                        <tr>
                            <td class="fw-semibold p-3">Complexion:</td>
                            <td class="fw-normal p-3">Fair</td>
                        </tr>
                        <tr>
                            <td class="fw-semibold p-3">Height:</td>
                            <td class="fw-normal p-3">5 feet 9 inches</td>
                        </tr>
                    </tbody>
                </table>
            </div>
            <div class="col-2"></div>
        </div>
        <p id="i2" class="h5 m-4 text-center">Professional Information</p>
        <div class="row  font-monospace">
            <div class="col-2"></div>
            <div class="col">
                <table class="table">
                    <thead>
                        <tr>
                            <th scope="col"></th>
                            <th scope="col" class="w-75"></th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td class="fw-semibold p-3">High-School</td>
                            <td class="fw-normal p-3">Random High School</td>
                        </tr>
                        <tr>
                            <td class="fw-semibold p-3">Undergrad</td>
                            <td class="fw-normal p-3">Random College info</td>
                        </tr>
                        <tr>
                            <td class="fw-semibold p-3">Post-graduation</td>
                            <td class="fw-normal p-3">Random Masters degree</td>
                        </tr>
                        <tr>
                            <td class="fw-semibold p-3">Occupation</td>
                            <td class="fw-normal p-3">Job</td>
                        </tr>
                        <tr>
                            <td class="fw-semibold p-3">Company Name</td>
                            <td class="fw-normal p-3">Oracle Systems</td>
                        </tr>
                        <tr>
                            <td class="fw-semibold p-3">Salary</td>
                            <td class="fw-normal p-3">$ 240,000 </td>
                        </tr>
                        <tr>
                            <td class="fw-semibold p-3">Company Role</td>
                            <td class="fw-semibld p-3">Software Engineer Level-3</td>
                        </tr>
                        <tr>
                            <td class="fw-semibold p-3">Company Location</td>
                            <td class="fw-normal p-3">Los Angeles, California</td>
                        </tr>
                        <tr>
                            <td class="fw-semibold p-3">Residential Status</td>
                            <td class="fw-normal p-3">U.S Citizen</td>
                        </tr>
                        <tr>
                            <td class="fw-semibold p-3">Visa Status</td>
                            <td class="fw-normal p-3">Citizenship</td>
                        </tr>
                    </tbody>
                </table>
            </div>
            <div class="col-2"></div>
        </div>
        <p id="i3" class="h4 m-4 text-center">Family Information</p>
        <div class="row  font-monospace">
            <div class="col-2"></div>
            <div class="col">
                <table class="table">
                    <thead>
                        <tr>
                            <th scope="col"></th>
                            <th scope="col" class="w-75"></th>
                        </tr>
                    </thead>
                    <tbody>
                        <tr>
                            <td class="fw-semibold p-3">Father Name</td>
                            <td class="fw-normal p-3">Margot Foster</td>
                        </tr>
                        <tr>
                            <td class="fw-semibold p-3">Father Occupation</td>
                            <td class="fw-normal p-3">Margot Foster</td>
                        </tr>
                        <tr>
                            <td class="fw-semibold p-3">Mother Name</td>
                            <td class="fw-normal p-3">+91 7898556643</td>
                        </tr>
                        <tr>
                            <td class="fw-semibold p-3">Mother Occupation</td>
                            <td class="fw-normal p-3">Margotfoster@gmailcom</td>
                        </tr>
                        <tr>
                            <td class="fw-semibold p-3">Siblings</td>
                            <td class="fw-normal p-3">23 May 1995</td>
                        </tr>
                        <tr>
                            <td class="fw-semibold p-3">Net worth(INR)</td>
                            <td class="fw-normal p-3">4:30pm</td>
                        </tr>
                        <tr>
                            <td class="fw-semibold p-3">Parents Address</td>
                            <td class="fw-semibld p-3">Hyderabad, India</td>
                        </tr>
                    </tbody>
                </table>
            </div>
            <div class="col-2"></div>
        </div>
        </div>
        <div class="row m-5"></div>
    </div>
</template>

<script>
export default {
    name: 'ProfilePart',
    props: {
        msg: String
    }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped></style>
