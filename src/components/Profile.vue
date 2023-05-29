<template>
    <div class="container">
        <p class="h5 m-4 mt-5 text-center">Applicant Information</p>
        <p class="h6 m-4 text-center">Personal Information</p>
        <div class="row">
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
                <p class="h6 m-4 mt-5 text-center">Professional Information</p>
            </div>
            <div class="col-2"></div>
            </div>
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
