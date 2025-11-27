<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy Birthday!</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <div class="container">
        <section id="title-screen" class="screen active">
            <h1>Happy Birthday to You! ❤️</h1>
            <p>Press to continue</p>
            <button onclick="showScreen('message-screen')">Continue</button>
        </section>

        <section id="message-screen" class="screen">
            <div class="note-paper">
                <h2>On this special day, I hope...</h2>
                <textarea readonly>
میری دعا ہے کہ خواہشوں کے سمندر کے سب موتی تیرا مقدر ہوں
پھول چہرے، پھول لہجے، تیرے ہمسفر ہوں
تیری سماعتوں کی دسترس میں کبھی وہ لفظ نہ آئے کہ تیرے دل کو ملال ہو

تیری بصارتوں میں ہر وہ منظر اترے جو روشن ہو صاحب جمال ہو تیرے شام و سحر تیرے برگ و ثمر تیرے لیل و نہار تیرے رنگ آرزو رخسار امڈتی بہاروں کی مثال ہو

کبھی یوں اترے تیرے لئے رحمتیں کہ تیری دعا کا حرف مدعا آسمانوں سے کبھی رد نہ ہو

تیرے نام کی دعاؤں میں شامل کسی کا کوئی حرف بد نہ ہو کہکشاں راستوں پہ پیہم رواں دواں رہے دعا ہے کہ تیری عمر کا ہر لمحہ روشن رہے۔


Happy Birthday, my love! ❤️
                </textarea>
                <button onclick="showScreen('proposal-screen')">Read More</button>
            </div>
        </section>

        <section id="proposal-screen" class="screen">
            <h2>Would you be mine forever?</h2>
            <div class="buttons">
                <button id="yes-btn" onclick="showScreen('final-screen')">YES! Of Course</button>
                <button id="no-btn">Soch ke btaungi</button> </div>
        </section>

        <section id="final-screen" class="screen">
            <h1>I Love You!</h1>
            <p>You made my heart the happiest!</p>
        </section>
    </div>

    <script src="script.js"></script>
</body>
</html>
