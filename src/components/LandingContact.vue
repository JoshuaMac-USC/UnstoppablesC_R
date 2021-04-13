<template>
        <div id="contact-section" class="bg-info p-4">
        <div class="row justify-content-center mt-3 mb-3">
            <div class="col-lg-4">
                <h2>Have any concerns?</h2>
                <p>Contact us by filling out the information below</p>
                <form>
                    <div class="form-group text-left">
                        <input type="email" class="form-control" placeholder="Enter your email"><br>
                        <textarea class="form-control" placeholder="Enter your message" rows="5" cols="50">   
                        </textarea>
                    </div>
                    <button class="submit-button" type="submit" >Submit Message</button>
                </form>
            </div>
        </div>
    </div>
</template>
<style scoped>
#contact-section{
    background-color: #57AEAF;
    text-align: center;
}
h2{
    text-align: center;
}
p{
    text-align: center;
}
.submit-button{
    background-color: green;
    border: none;
}
</style>