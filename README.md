# Definisi CSS

> CSS adalah singkatan dari Cascading Style Sheet,Pada umumnya Css digunakan untuk mendesign suatu website atau memeberikan style pada website agar terlihat lebih menarik.

# Css Syntax

> Aturan main dari penggunaan Css adalah menggunakan sebuah <i>Selector</i> dan <i>block declaration</i> seperti gambar berikut :
<img src="https://www.w3schools.com/css/selector.gif"/> <br/> dimana <code>h1</code> adalah sebuah selector yang akan diberikan property atau style dengan css yang ada di dalam block declaration tersebut.block declaration pada Css dapat ditulis dengan <code>{isi property Css}</code>

# Selector id dan class

> Untuk dapat menggunakan css secara baik dan benar kita dapat menggunakan <code>id dan class </code> untuk mendeklarasikan style pada selector yang kita butuhkan,untuk penggunaan id pada css dapat ditulis dengan tanda<code>#</code>dan untuk class dapat ditulis dengan <code>.</code> contoh impelemntasinya : 
<code>

    <h1 id="warna">
        memeberikan warna pada h1
    </h1>
    <h2 class="warna">
        memeberikan warna pada h1
    </h2>
    /*
    contoh kode css
    */
    h1#warna {
        color: blue;
    }
    h2.warna {
        color: red;
    }
</code>
pada contoh di atas kita sudah mendeklarasikan bagaiman penggunaan id dan class pada css. 

# Css Grouping Selector

> Grouping selector adalah penggunaan teknik css dimana kita tidak perlu memberikan id atau class pada selector HTML,bila kita ingin menggunakan Grouping Selector cukup tuliskan saja tag HTML pada Css nya,berikut Contohnya : 
<code>

    <h1>menggunakan Grouping Selector</h1>
    /*
    *   css dengan Grouping Selector
    */
    h1 {
        color : red;
    }

</code>
<br>
Pada intinya kita hanya perlu menuliskan selector HTML nya saja dengan begitu seluruh selector yang telah ditulis dalam css akan memiliki style yang sama.

# CSS How To

> Bagaimana menggunakan Css ???? terdapat tiga cara dalam menggunakan css :

- External Style Sheet
- Internal Style Sheet
- Inline Style Sheet

Cara Penggunaan masing-masing :
<br> 
External Style Sheet  
<code>

    <head>
        <link rel="stylesheet" type="text/css" href="mystyle.css">
    </head>

</code>
<br>
Internal Style Sheet  
<code>
    
    <head>
        <style>
        body {
            background-color: linen;
        }

        h1 {
            color: maroon;
            margin-left: 40px;
        } 
        </style>
    </head>

</code>

<br> 
Inline Style Sheet  
<code>

    <h1 style="color:blue;margin-left:30px;">This is a heading</h1>

</code>

# Css color

> Ada beberapa property css yang sering digunakan untuk memberikan warna pada tulisan maupun background pada website. Berikut beberapa property yang sering digunakan : 
<br>

<code>
    
    <h1>pemeberian warna pada tulisan dan background warna
    <style>

        h1 {
            color: blue;
            background-color:red
        }
        
    </style>


</code>

# Css background image

> Selain memberikan warna pada css kita juga dapat membuat background menggunakan gambar dengan css, berikut contohnya : 

<code>

    <body>memberikan backgrond pada body webiste</body>

    <style>
        body {
            background-image: url("1.jpg");
        }
    </style>


</code>

# Css Border

> Dengan menggunakan Css Border kita dapat memberikan style berupa garis pada selector HTML, berikut contohnya : 
<code>

    <p>berikan border pada paragraph ini</p>
    <style>
        <p>
            p.solid {border-style: solid;}
        </p>
    </style>


</code>

Untuk sumber lengkap silahkan kunjungi <a href="https://www.w3schools.com/css/css_border.asp">Border</a>