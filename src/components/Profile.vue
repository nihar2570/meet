<template>
    <div class="container">
        
        <!-- images div -->
        <hr class="border border-info border-1 opacity-25">   
        <p class="h5 text-center">Daniel Wheatley</p>
        <hr class="border border-info border-1 opacity-25">   
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

        <!-- personal info -->
        <hr class="mt-4 border border-info border-1 opacity-25">   
        <p id="i1" class="h5 m-4 text-center">Personal Information</p>
        <hr class="border border-info border-1 opacity-25">   
        <div class="row justify-content-center">
            <div class="col-lg-6 col-md-8 col-sm-10">
            <div class="card border-light shadow-sm">
                <div class="card-body">
                    <dl class="row font-monospace">
                        <dt class="col-sm-4">Full Name:</dt>
                        <dd class="col-sm-7">Daniel H. Wheatly</dd>
                        <dt class="col-sm-4">Phone Number:</dt>
                        <dd class="col-sm-8">+91 9848776655</dd>
                        <dt class="col-sm-4">Email ID:</dt>
                        <dd class="col-sm-8">daniel.wheatley@gmail.com</dd>            
                        <dt class="col-sm-4">Date of Birth:</dt>
                        <dd class="col-sm-8">23 May 1995</dd>
                        <dt class="col-sm-4">Time of Birth:</dt>
                        <dd class="col-sm-8">4:30pm</dd>
                        <dt class="col-sm-4">Place of Birth:</dt>
                        <dd class="col-sm-8">Hyderabad, India</dd>
                        <dt class="col-sm-4">Gothram:</dt>
                        <dd class="col-sm-8">gothram</dd>
                        <dt class="col-sm-4">Birth Star:</dt>
                        <dd class="col-sm-8">starname</dd>
                        <dt class="col-sm-4">Zodiac Sign:</dt>
                        <dd class="col-sm-8">Aquarius</dd>
                        <dt class="col-sm-4">Complexion:</dt>
                        <dd class="col-sm-8">Fair</dd>
                        <dt class="col-sm-4">Height:</dt>
                        <dd class="col-sm-8">5 feet 9 inches</dd>
                        <dt class="col-sm-4">Weight:</dt>
                        <dd class="col-sm-8">75 kgs</dd>
                    </dl>
                </div>
            </div>
            </div>
        </div>

        <!-- professional info -->
        <hr class="mt-5 border border-info border-1 opacity-25">   
        <p id="i2" class="h5 m-4 text-center">Professional Information</p>
        <hr class="border border-info border-1 opacity-25">   
        <div class="row justify-content-center">
            <div class="col-lg-6 col-md-8 col-sm-10">
            <div class="card border-light shadow-sm" >
                <div class="card-body">
                    <dl class="row font-monospace">
                        <dt class="col-sm-4">High-School:</dt>
                        <dd class="col-sm-8">ABC Elementary High</dd>
                        <dt class="col-sm-4">Undergrad:</dt>
                        <dd class="col-sm-8">CBIT Hyderabad (CSE)</dd>
                        <dt class="col-sm-4">Post-graduation:</dt>
                        <dd class="col-sm-8">Univeristy of California, LA</dd>            
                        <dt class="col-sm-4">Profession:</dt>
                        <dd class="col-sm-8">Software Employee</dd>
                        <dt class="col-sm-4">Company:</dt>
                        <dd class="col-sm-8">Oracle Systems</dd>
                        <dt class="col-sm-4">Company Role:</dt>
                        <dd class="col-sm-8">level-3 Sr.software Developer</dd>
                        <dt class="col-sm-4">Salary:</dt>
                        <dd class="col-sm-8">$240,000</dd>
                        <dt class="col-sm-4">Company Location:</dt>
                        <dd class="col-sm-8">Los Angeles, California</dd>
                        <dt class="col-sm-4">Residential Status:</dt>
                        <dd class="col-sm-8">U.S Citizen</dd>
                    </dl>
                </div>
            </div>
            </div>
        </div>

        <!-- family info -->
        <hr class="mt-5 border border-info border-1 opacity-25">   
        <p id="i3" class="h5 m-4 text-center">Family Information</p>
        <hr class="border border-info border-1 opacity-25">   
        <div class="row justify-content-center">
            <div class="col-lg-6 col-md-8 col-sm-10">
            <div class="card border-light shadow-sm" >
                <div class="card-body">
                    <dl class="row font-monospace">
                        <dt class="col-sm-4">Father Name:</dt>
                        <dd class="col-sm-8">Mark Foster</dd>
                        <dt class="col-sm-4">Father Occupation:</dt>
                        <dd class="col-sm-8">Goverment Employee</dd>
                        <dt class="col-sm-4">Mother Name:</dt>
                        <dd class="col-sm-8">Michelle Foster</dd>            
                        <dt class="col-sm-4">Mother Occupation:</dt>
                        <dd class="col-sm-8">Housewife</dd>
                        <dt class="col-sm-4">Siblings:</dt>
                        <dd class="col-sm-8">1 brother</dd>
                        <dt class="col-sm-4">Parents address:</dt>
                        <dd class="col-sm-8">Hyderabad, india</dd>
                        <dt class="col-sm-4">net-worth($)</dt>
                        <dd class="col-sm-8">5 Million</dd>
                    </dl>
                </div>
            </div>
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
