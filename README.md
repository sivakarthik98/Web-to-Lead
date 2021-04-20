<html xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" lang="en">
        <style>
            body,html {
            background-image: url("https://ak.picdn.net/shutterstock/videos/3614222/thumb/3.jpg");
            height: 130%;
            background-position: center;
            background-repeat: no-repeat;
            background-size: cover;
            }
        </style>
        <head>
            <meta charset="utf-8" />
            <meta http-equiv="x-ua-compatible" content="ie=edge" />
            <title>ACME Lead Generator</title>
            <meta name="viewport" content="width=device-width, initial-scale=1" />
            <META HTTP-EQUIV="Content-type" CONTENT="text/html; charset=UTF-8"/>
            <script>
            function timestamp() { var response = document.getElementById("g-recaptcha-response"); if (response == null || response.value.trim() == "") {var elems = JSON.parse(document.getElementsByName("captcha_settings")[0].value);elems["ts"] = JSON.stringify(new Date().getTime());document.getElementsByName("captcha_settings")[0].value = JSON.stringify(elems); } } setInterval(timestamp, 500); 
            </script>
            <!-- CSS only -->
            <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.0-beta2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-BmbxuPwQa2lc/FVzBcNJ7UAyJxM6wuqIj61tLrc4wSX0szH/Ev+nYRRuWlolflfl" crossorigin="anonymous"/>
            <!-- Import the Design System style sheet -->
            <apex:slds />
        </head>
        
        
        <body>
            
            
            <figure class="text-center">
                <blockquote class="blockquote">
                    <p>ACME Lead Generator</p>
                </blockquote>
                <figcaption class="blockquote-footer" >
                    WELCOME TO ACME 
                </figcaption>
            </figure>
            <div class="row justify-content-center align-items-center">
                
                <div class="col-6 col-md-6 col-lg-6">
                    
                    <form action="https://test.salesforce.com/servlet/servlet.WebToLead?encoding=UTF-8" method="POST">
                       
                        <input type="hidden" name="oid" value="00D1s0000008qha"/>
                        <input type="hidden" name="retURL" value="https://sivakarthik98.github.io/ACME/"/>
                        
                        <div class="form-group">
                            <label class="col-sm-3" for="first_name validationServer01">First Name</label>
                            <div class="col-sm-5">
                                <input class="form-control " id="first_name " required="true" maxlength="40" name="first_name" size="20" type="text"/><br/>
                            </div>
                        </div>
                        <div class="form-group">
                            <label class="col-sm-3" for="last_name validationServer02">Last Name</label>
                            <div class="col-sm-5">
                                <input class="form-control"  id="last_name" required="true" maxlength="80" name="last_name" size="20" type="text" /><br/>
                            </div>
                        </div>
                        
                        <div class="form-group">
                            <label class="col-sm-3" for="email exampleInputEmail1">Email</label>
                            <div class="col-sm-5">
                                <input class="form-control"  id="email exampleInputEmail1" requried="true" maxlength="80" name="email" size="20" type="email" /><br/>
                            </div>
                        </div>
                        <div class="form-group">
                            <label class="col-sm-3" for="phone">Phone</label>
                            <div class="col-sm-5">
                                <input class="form-control"  id="phone" maxlength="40" name="phone" size="20" type="phone" required="true" /><br/>
                            </div>
                        </div>
                        
                        <div class="form-group">
                            <label class="col-sm-3" for="company ">Company</label>
                            <div class="col-sm-5">
                                <input class="form-control" id="company" maxlength="40" name="company" size="20" type="text" /><br/>
                            </div>
                        </div>
                        
                        
                        
                        <div class="col-sm-5">
                            Product Type:<select class="form-select"  id="00N1s000001LHdg" name="00N1s000001LHdg" title="Product Type" >
                            <option value="">--None--</option>
                            <option value="Residential">Residential</option>
                            <option value="Commercial">Commercial</option>
                            </select><br/>
                            <div class="invalid-feedback">Example invalid select feedback</div>
                        </div>
                        
                        <div class="col-sm-5">
                            City:<select class="form-select" id="00N1s000001LHdq validationServer04" requried="true" name="00N1s000001LHdq" title="City">
                            <option value="">--None--</option>
                            <option value="Bangalore">Bangalore</option>
                            <option value="Mumbai">Mumbai</option>
                            </select><br/>
                        </div>
                       <div class="g-recaptcha" data-sitekey="6Lewa7EaAAAAAMxnx4yRBxd37bRzzXc0LKgVD2JZ"></div><br>
                        <button type="submit"  class="btn btn-primary">Submit</button>
                        
                    </form> 
                </div>
            </div>
            
        </body>
    </html>
