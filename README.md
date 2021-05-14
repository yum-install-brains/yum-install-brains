<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>new.css Demo</title>
    <meta name="description" content="A classless CSS framework to write modern websites using only HTML.">
    <meta name="keywords" content="newcss,new.css,css,xz,css framework,classless css,xz.style">
    <meta property="og:title" content="new.css">
    <meta property="og:description" content="A classless CSS framework to write modern websites using only HTML.">
    <meta property="og:url" content="https://newcss.net">
    <meta property="og:type" content="website">
    <meta property="og:image" content="https://newcss.net/_assets/og.png">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@exampledev/new.css@1/new.min.css">
    <link rel="stylesheet" href="https://newcss.net/theme/terminal.css">
</head>
<body>
    <header>
        <h1>new.css Demo</h1>
    </header>

    <h1>Heading 1</h1>
    <p>This is paragraph text. Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
    <h2>Heading 2</h2>
    <p>This is paragraph text. Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
    <h3>Heading 3</h3>
    <p>This is paragraph text. Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
    <h4>Heading 4</h4>
    <p>This is paragraph text. Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
    <h5>Heading 5</h5>
    <p>This is paragraph text. Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
    <h6>Heading 6</h6>
    <p>This is paragraph text. Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>

    <br>
    <hr>
    <br>

    <p>
        Lorem <mark>ipsum</mark> dolor sit amet <strong>consectetur</strong> adipisicing elit. Aut <i>harum
            molestias</i> labore amet
        possimus <s>exercitationem aperiam</s> earum, doloribus <u>nobis ducimus</u> maiores quia voluptates quis omnis
        molestiae quisquam. <a href="#">Voluptatibus, officiis laudantium?</a>
    </p>

    <p>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. <code>Hic culpa, nobis doloremque</code> veniam non,
        nihil
        cupiditate odit repellat est <kbd>ALT + F4</kbd> expedita facilis. Fuga aspernatur, alias debitis eveniet totam
        minima vel.
    </p>

    <ul>
        <li>List item</li>
        <li>List item</li>
        <li>List item</li>
        <li>List item</li>
    </ul>

    <ol>
        <li>Step 1</li>
        <li>Step 2</li>
        <li>????</li>
        <li>PROFIT!!!</li>
    </ol>

    <dl>
        <dt>Web</dt>
        <dd>The part of the Internet that contains websites and web pages</dd>
        <dt>HTML</dt>
        <dd>A markup language for creating web pages</dd>
        <dt>CSS</dt>
        <dd>A technology to make HTML look better</dd>
    </dl>

    <blockquote cite="https://en.wikiquote.org/wiki/Edward_Snowden">
        If you think privacy is unimportant for you because you have nothing to hide, you might as well say free speech
        is unimportant for you because you have nothing useful to say.<br><br>– Edward Snowden
    </blockquote>

    <pre>
&#x3C;!DOCTYPE html&#x3E;
&#x3C;html&#x3E;
    &#x3C;head&#x3E;
    &#x3C;title&#x3E;Hello World&#x3C;/title&#x3E;
    &#x3C;/head&#x3E;
    &#x3C;body&#x3E;
    &#x3C;p&#x3E;Lorem ipsum dolor sit amet, consectetur adipiscing elit.&#x3C;/p&#x3E;
    &#x3C;/body&#x3E;
&#x3C;/html&#x3E;</pre>

    <br>
    <hr>
    <br>

    <table>
        <caption>Ho-kago Tea Time</caption>
        <thead>
            <tr>
                <th>Name</th>
                <th>Instrument</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Yui Hirasawa</td>
                <td>Lead Guitar</td>
            </tr>
            <tr>
                <td>Mio Akiyama</td>
                <td>Bass</td>
            </tr>
            <tr>
                <td>Ritsu Tainaka</td>
                <td>Drums</td>
            </tr>
            <tr>
                <td>Tsumugi Kotobuki</td>
                <td>Keyboard</td>
            </tr>
            <tr>
                <td>Azusa Nakano</td>
                <td>Rhythm Guitar</td>
            </tr>
        </tbody>
        <tfoot>
            <tr>
                <th>Name</th>
                <th>Instrument</th>
            </tr>
        </tfoot>
    </table>

    <br>
    <hr>
    <br>

    <form>
        <p><em>This is not a real form and does not submit or save any information.</em></p>
        <p>
            <label>First name</label><br>
            <input type="text" name="first_name">
        </p>
        <p>
            <label>Last name</label><br>
            <input type="text" name="last_name">
        </p>
        <p>
            <label>Gender</label><br>
            <label>
                <input type="radio" name="gender" value="Male">
                Male
            </label>
            <br>
            <label>
                <input type="radio" name="gender" value="Female">
                Female
            </label>
            <br>
            <label>
                <input type="radio" name="gender" value="other-none-na">
                Non-binary
            </label>
        </p>
        <p>
            <label>Email</label><br>
            <input type="email" name="email" required="">
        </p>
        <p>
            <label>Phone number</label><br>
            <input type="tel" name="phone">
        </p>
        <p>
            <label>Password</label><br>
            <input type="password" name="password">
        </p>
        <p>
            <label>Country</label><br>
            <select>
                <option>China</option>
                <option>India</option>
                <option>United States</option>
                <option>Indonesia</option>
                <option>Brazil</option>
            </select>
        </p>
        <p>
            <label>Comments</label><br>
            <textarea></textarea>
        </p>
        <p>
            <label>
                <input type="checkbox" value="terms">
                I agree to the <a>terms and conditions</a>
            </label>
        </p>
        <p>
            <button>Sign up</button>
            <button type="reset">Reset form</button>
            <button disabled="disabled">Disabled</button>
        </p>
    </form>

    <br>
    <hr>
    <br>

    <img src="https://elements.xz.style/assets/fuji-daniel-hehn.jpg" alt="Mt. Fuji">

    <script async defer src="https://api.newcss.net/latest.js"></script>
    <noscript><img src="https://api.newcss.net/noscript.gif" alt=""></noscript>
</body>

</html>
