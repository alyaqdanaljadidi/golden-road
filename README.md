<!DOCTYPE html>

<html lang="ar" dir="rtl">

<head>

    <meta charset="UTF-8">

    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Golden Road - غسيل السيارات</title>

    <style>

        body {

            font-family: Arial, sans-serif;

            margin: 0;

            padding: 0;

            background: url('car-wash-background.jpg') no-repeat center center fixed;

            background-size: cover;

            color: #fff;

        }

        .container {

            max-width: 800px;

            margin: 50px auto;

            background: rgba(0, 0, 0, 0.7);

            padding: 20px;

            border-radius: 10px;

        }

        h1 {

            text-align: center;

            color: gold;

        }

        form {

            display: flex;

            flex-direction: column;

            gap: 15px;

        }

        label {

            font-size: 1.2em;

        }

        input, select, button {

            padding: 10px;

            font-size: 1em;

            border-radius: 5px;

            border: none;

            outline: none;

        }

        button {

            background-color: gold;

            color: black;

            cursor: pointer;

            font-weight: bold;

        }

        button:hover {

            background-color: #fff;

        }

        .payment-methods {

            display: flex;

            gap: 10px;

        }

        .payment-methods div {

            background: #333;

            padding: 10px;

            border-radius: 5px;

        }

    </style>

</head>

<body>

    <div class="container">

        <h1>Golden Road - غسيل السيارات</h1>

        <form id="bookingForm">

            <label for="name">الاسم:</label>

            <input type="text" id="name" name="name" placeholder="أدخل اسمك" required>



            <label for="plateNumber">رقم اللوحة:</label>

            <input type="text" id="plateNumber" name="plateNumber" placeholder="أدخل رقم اللوحة" required>



            <label for="phoneNumber">رقم الهاتف:</label>

            <input type="tel" id="phoneNumber" name="phoneNumber" placeholder="أدخل رقم الهاتف" required>



            <label for="packageType">نوع الباقة:</label>

            <select id="packageType" name="packageType" required>

                <option value="basic">الباقة الأساسية</option>

                <option value="premium">باقة التميز</option>

                <option value="vip">باقة VIP</option>

                <option value="monthly">باقة الاشتراك الشهري</option>

            </select>



            <div class="payment-methods">

                <div>

                    <input type="radio" id="cash" name="paymentMethod" value="cash" required>

                    <label for="cash">الدفع نقدًا</label>

                </div>

                <div>

                    <input type="radio" id="number" name="paymentMethod" value="number" required>

                    <label for="number">عن طريق الرقم</label>

                </div>

            </div>



            <button type="submit">احجز الآن</button>

        </form>

    </div>



    <script>

        document.getElementById('bookingForm').addEventListener('submit', function(e) {

            e.preventDefault();



            const name = document.getElementById('name').value;

            const plateNumber = document.getElementById('plateNumber').value;

            const phoneNumber = document.getElementById('phoneNumber').value;

            const packageType = document.getElementById('packageType').value;

            const paymentMethod = document.querySelector('input[name="paymentMethod"]:checked').value;



            const message = `الاسم: ${name}\nرقم اللوحة: ${plateNumber}\nرقم الهاتف: ${phoneNumber}\nنوع الباقة: ${packageType}\nطريقة الدفع: ${paymentMethod}`;

            

            // إرسال التفاصيل إلى الرقم

            window.open(`https://wa.me/96636098?text=${encodeURIComponent(message)}`);

        });

    </script>

</body>

</html>          اجعل لي رابط لكي يستخدمه الناس يكون اسمه Golden Road <!DOCTYPE html>

<html lang="ar" dir="rtl">

<head>

    <meta charset="UTF-8">

    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Golden Road - غسيل السيارات</title>

    <style>

        body {

            font-family: Arial, sans-serif;

            margin: 0;

            padding: 0;

            background: url('car-wash-background.jpg') no-repeat center center fixed;

            background-size: cover;

            color: #fff;

        }

        .container {

            max-width: 800px;

            margin: 50px auto;

            background: rgba(0, 0, 0, 0.7);

            padding: 20px;

            border-radius: 10px;

        }

        h1 {

            text-align: center;

            color: gold;

        }

        form {

            display: flex;

            flex-direction: column;

            gap: 15px;

        }

        label {

            font-size: 1.2em;

        }

        input, select, button {

            padding: 10px;

            font-size: 1em;

            border-radius: 5px;

            border: none;

            outline: none;

        }

        button {

            background-color: gold;

            color: black;

            cursor: pointer;

            font-weight: bold;

        }

        button:hover {

            background-color: #fff;

        }

        .payment-methods {

            display: flex;

            gap: 10px;

        }

        .payment-methods div {

            background: #333;

            padding: 10px;

            border-radius: 5px;

        }

    </style>

</head>

<body>

    <div class="container">

        <h1>Golden Road - غسيل السيارات</h1>

        <form id="bookingForm">

            <label for="name">الاسم:</label>

            <input type="text" id="name" name="name" placeholder="أدخل اسمك" required>



            <label for="plateNumber">رقم اللوحة:</label>

            <input type="text" id="plateNumber" name="plateNumber" placeholder="أدخل رقم اللوحة" required>



            <label for="phoneNumber">رقم الهاتف:</label>

            <input type="tel" id="phoneNumber" name="phoneNumber" placeholder="أدخل رقم الهاتف" required>



            <label for="packageType">نوع الباقة:</label>

            <select id="packageType" name="packageType" required>

                <option value="الأساسية">الباقة الأساسية</option>

                <option value="التميز">باقة التميز</option>

                <option value="vip">باقة VIP</option>

                <option value="الاشتراك الشهري">باقة الاشتراك الشهري</option>

            </select>



            <div class="payment-methods">

                <div>

                    <input type="radio" id="cash" name="paymentMethod" value="cash" required>

                    <label for="cash">الدفع نقدًا</label>

                </div>

                <div>

                    <input type="radio" id="number" name="paymentMethod" value="number" required>

                    <label for="number">عن طريق الرقم</label>

                </div>

            </div>



            <button type="submit">احجز الآن</button>

        </form>

    </div>



    <script>

        document.getElementById('bookingForm').addEventListener('submit', function(e) {

            e.preventDefault();



            const name = document.getElementById('name').value;

            const plateNumber = document.getElementById('plateNumber').value;

            const phoneNumber = document.getElementById('phoneNumber').value;

            const packageType = document.getElementById('packageType').value;

            const paymentMethod = document.querySelector('input[name="paymentMethod"]:checked').value;



            const message = `الاسم: ${name}\nرقم اللوحة: ${plateNumber}\nرقم الهاتف: ${phoneNumber}\nنوع الباقة: ${packageType}\nطريقة الدفع: ${paymentMethod}`;

            

            // إرسال التفاصيل إلى الرقم

            window.open(`https://wa.me/96636098?text=${encodeURIComponent(message)}`);

        });

    </script>

</body>

</html>
