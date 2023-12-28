<!doctype html>
<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Bootstrap demo</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-T3c6CoIi6uLrA9TneNEoa7RxnatzjcDSCmG1MXxSR1GAsXEV/Dwwykc2MPK8M2HN" crossorigin="anonymous">
	  
	<style>
	  /* Background Colors */
 .my-heading,
 .my-nav,
 .my-footer {
     background-color: #1339e6;

 }

 .my-customer-detatils {
     background-color: #dceb09;

 }

 .my-repair-details {
     background-color: #807c7f;

 }

 .my-courtesyItem {
     background-color: #5bb1e2;

 }

 .my-cost {
     background-color: #72e25b;

 }
.my-buttons {
     background-color: #232aae;

 }
 .content {
            min-height: 300px;
        }

        .myCssForm {
            border: 2px solid rgb(149, 30, 30);
            border-radius: 8px;
            padding: 5px;
        }

        .myCssForm legend {
            font-weight: bold;
        }

        .myCssForm label {
            display: block;
            margin-bottom: 1px;
        }

        .myCssForm input[type="radio"] {
            margin-right: 5px;
        }

        .custom-table {
            width: 60%;
            margin: 20px 0 0 20px;
            border-collapse: collapse;
            background-color: #fff;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        .custom-table th,
        .custom-table td {
            padding: 10px;
            text-align: left;
            border-bottom: 1px solid #ddd;
        }

        .custom-table th {
            background-color: #007BFF;
            color: #fff;
        }



        .addButton {
            padding: 15px 30px;
            font-size: 18px;
            background-color: #3aace6;
            color: #3a2121;
            border: none;
            border-radius: 8px;
            cursor: pointer;
        }

        .my-buttons {
            text-align: center;
        }

        .button-container {
            display: flex;
            justify-content: center;
            margin-top: 10px;
        }

        .center-button {
            padding: 10px 20px;
            margin: 0 10px;
            font-size: 16px;
            background-color: #007BFF;
            color: #fff;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }

        .center-text {
            font-size: 18px;
            color: #555;
            margin-top: 10px;
            text-align: center;
        }

        .aligned-form {
            display: flex;
            align-items: center;
            margin-bottom: 10px;
        }

        label {
            min-width: 200px;
            margin-right: 10px;
        }

        input,
        select
        textarea {
            width: 50%;
            padding: 5px;
            box-sizing: border-box;
            margin-bottom: 10px;
        }
</style>
  </head>
  <body>
    <div class="container-fluid">
	<div class="row">
		<div class="col-md-8 my-heading">
			<h3>
				Logitech Mouse Store
			</h3>
		</div>
		<div class="col-md-4 my-nav">
			<h3>
				<a href="V1 Student File Xu.html">Home/Extention</a>
			</h3>
		</div>
	</div>
	  </div>
	<div class="row">
		<div class="col-md-12">
			<div class="row">
				<div class="col-md-4 my-customer-detatils">
					<h3>
						Customer Details
					</h3>
					<h4>Customer type</h4>
			 <form>
             <input type="radio" id="html" name="fav_language" value="HTML">
             <label for="html">Consumer</label><br>
             <input type="radio" id="css" name="fav_language" value="CSS">
             <label for="css">Suppliers</label><br>
			 <br>
		     <label for="country">Title:</label>
             <select id="country" name="country">
             <option value="China">Chairman</option>
             <option value="New Zealand">CEO</option>
             <option value="Britain">Manger</option>
             <option value="America">Employee</option>
             </select><br><br>
			 <label for="fname">First name:</label>
			 <center><input type="text" id="fname" name="fname" value=""></center><br>
             <label for="lname">Last name:</label>
             <center><input type="text" id="lname" name="lname" value=""></center><br>
		     <label for="Street">Street:</label>
             <center><input type="text" id="Street" name="Street" value=""></center><br>
			 <label for="Suburb">Suburb:</label>
			 <center><input type="text" id="Suburb" name="Suburb" value=""></center><br>
			 <label for="city">City:</label>
			 <center><input type="text" id="city" name="city" value=""></center><br>
			 <label for="post code">Post Code:</label>
			 <center><input type="text" id="post code" name="post code" value=""></center><br>
             <label for="telephone number">Phone Number:</label>
             <center><input type="number" id="telephone number" name="telephone number" value=""></center><br>
             <label for="email">Email:</label>
             <center><input type="email" id="email" name="email"></center><br>
			 <input type="reset"  value="Reset">
             </form>
			 
				</div>
				<div class="col-md-4 my-repair-details">
					<h3>
						Repair Detials
					</h3>
					<form action="/action_page.php">
                    <label for="Purchase date">Purchase Date:</label>
                    <center><input type="date" id="Purchase date" name="Purchase date"></center><br>
                    <label for="Repair date">Repair Date:</label>
                    <center><input type="date" id="Repair date" name="Repair date"></center><br>
					<input type="checkbox" id="vehicle1" name="vehicle1" value="Bike">
                    <label for="vehicle1"> Under Warranty</label><br><br>
					<label for="serial">Serial Number:</label>
                    <center><input type="number" id="serial" name="serial" value=""></center><br>
					<label for="make">Make:</label>
					<center><select class="make" id="make"><br>
					<option value="select">Select Make</option>
					</select></center><br>
					<label for="faulty">Faulty Category:</label>
					<center><select class="faulty" id="faulty"><br>
					<option value="select">Select Fault</option>
					</select></center><br>
					<label for="problem">Description of Problem:</label>
                    <center><input type="text" id="problem" name="problem" value=""></center><br>
					 <input type="reset" value="Reset">
					</form>
				</div>
				<div class="col-md-4 col-12 p-0 m-0 ">
						<div class="my-courtesyItem" style="min-height: 30vh">
							<h3>
								Courtesy Item
							</h3>
                            <label for="weapon-select">Choose a weapon:</label>
                            <select id="weapon-select" class="form-control mb-3">
                                <option value="200">MX MASTER 3S $200</option>
								<option value="300">MX MASTER 3S FOR MAC $300</option>
								<option value="1000">M720 TRIATHLON $1000</option>
                            </select>
                            <!-- Add Weapon Button -->
                            <button id="addWeaponButton" class="btn btn-primary" type="button">Add Weapon</button><br>
                            
                            <div class="table-section">
                                <table class="table" id="weaponsTable">
                                    <thead>
                                        <tr>
                                            <th>Item</th>
                                            <th>Cost</th>
                                        </tr>
                                    </thead>
                                    <tbody id="tableContent">
                                        <!-- Weapon items will be added here -->
                                    </tbody>
                                </table>
                            </div>
						</div>
						<div class="my-cost" style="min-height:  70vh">
							<h3>
								Cost
							</h3>
						<form action="/action_page.php">
                        <label for="bond">Bond:</label>
                        <center><input type="text" id="bond" name="bond" value="$0.00"></center><br>
                        <label for="fee">Service Free:</label>
                        <center><input type="text" id="fee" name="fee" value="$0.00"></center><br>
						<label for="total">Total:</label>
                        <center><input type="text" id="total" name="total" value="$0.00"></center><br>
						<label for="tax">Tax:</label>
                        <center><input type="text" id="tax" name="tax" value="$0.00"></center><br>
						<label for="+">Total(+Tax):</label>
                        <center><input type="text" id="+" name="+" value="$0.00"></center><br>
					    <input type="reset" value="Reset">
						</form>
						</div>
				</div>
			</div>
		</div>
	</div>
	<div class="row">
		<div class="col-md-12 my-buttons">
			<h3>
				Buttons
			</h3>
			<input name="submit" type="Submit" id="submit" value="Submit All" formaction="维修.txt" formmethod="get">
			<button onclick="resetForms()">Reset All</button>
			<script>
function resetForms() {
  document.querySelectorAll('form').forEach(form => {
    form.reset();
  });
}
</script>
			<div class="row p-2" id="footerContent">
            <div class="col-md-12">
                <p>Change Colors (Header/Footer)</p>
                <input type="color" id="colorPicker">
            <div class="mb-2">
                <button type="button" class="btn btn-primary" id="saveColorBtn">Save Colors</button>
                <button type="button" class="btn btn-secondary" id="clearColorBtn">Clear Colors</button>
                <button type="button" class="btn btn-secondary ml-4" id="returnBtn">Return</button>
                <button type="button" class="btn btn-primary" id="translateBtn">Translate</button>
				</div>
    </div>
				</div>
	</div>
	<div class="row">
		<div class="col-md-12 my-footer">
			<h3>
				Footer
			</h3>
			<p align="center">@Created by:Gucheng Xu</p>
				<p align="center">
                    Contact me at:2458464652@qq.com
                </p>
		</div>
	</div>
</div>
  </body>
</html>
