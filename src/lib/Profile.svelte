<script>
    import profilePic from "$lib/profilepic.png"
</script>

<div class="flex flex-col justify-center items-center h-full w-full">
    <div class="flex justify-center items-center w-full h-60">
        <!-- svelte-ignore a11y-img-redundant-alt -->
        <img class=" w-full h-full object-contain" src={profilePic} alt="Profile Picture">
    </div>
    <div class="flex flex-col justify-center items-center w-2/3 h-2/3 pt-10">
       <div class="name flex flex-col text-4xl items-center text-justify font-bold w-full h-fit mb-4"><span>Sreeyush Poluri</span><span class="opacity-80 text-base">(catfo)</span></div>
       <div class="contact-info flex flex-col text-center text-xl font-bold"><span>BITS Hyderabad | Web Developer | Programmer</span><a class="mail hover:underline" href="mailto:f20220274@hyderabad.bits.pilani.ac.in">f20220274@hyderabad.bits.pilani.ac.in</a></div>
       <div class="aboutme flex text-lg text-center h-full p-2 mt-2">Richard hails from Tulsa. He has earned degrees from the University of Oklahoma and Stanford. Before starting Pied Piper, he worked for Hooli as a part time software developer</div>
    </div>
</div>