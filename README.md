<!DOCTYPE html>
<html>
    <head>
        <title>Membuat Tabel pada HTML</title>
        <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
        <style>
            * {
                font-family:'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
            }
            #tabel1 tr td {
                border: 1.5px solid black;
                width: 100px;
                height: 60px;
                padding: 5px;
            }
            textarea {
                width: 235px;
                height: 150px;
            }
            p {
                text-indent: 7%;
                text-align: justify;
                padding-left: 10px;
                width: 70%;
            }
        </style>
    </head>
    <body>
        <h2>Daftar Isi Web</h2>
        <ul>
            <li><a href="#tabel">Membuat Tabel</a></li>
            <li><a href="#form_tabel">Form Tabel</a></li>
            <li><a href="#teks_pertama">Teks Pertama</a></li>
            <li><a href="#teks_kedua">Teks Kedua</a></li>
        </ul>
        <h2 id="tabel">Membuat Tabel</h2>
        <table id="tabel1" cellspacing="0">
            <tr>
                <td>1,1</td>
                <td>1,2</td>
                <td>1,3</td>
                <td>1,4</td>
            </tr>
            <tr>
                <td>2,1</td>
                <td colspan="2" rowspan="2">Colspan dan Rowspan</td>
                <td>2,4</td>
            </tr>
            <tr>
                <td>3,1</td>
                <td>3,4</td>
            </tr>
            <tr>
                <td>4,1</td>
                <td>4,2</td>
                <td>4,3</td>
                <td>4,4</td>
            </tr>
        </table>
        <br><br>
        <h3 id="form_tabel">Form dengan Tabel</h3>
        <form>
            <table>
                <tr>
                    <td>
                        <label for="username">Nama : </label>
                    </td>
                    <td>
                        <input type="text" id="username" placeholder="Nama lengkap"/>
                    </td>
                </tr>
                <tr>
                    <td>
                        <label for="pwd">Password : </label>
                    </td>
                    <td>
                        <input type="password" id="pwd" placeholder="Password"/>
                    </td>
                </tr>
                <tr>
                    <td colspan="2">Jenis Kelamin (Pilih Salah Satu)</td>
                </tr>
                <tr>
                    <td>
                        <input type="radio" name="jnsklmn" id="pria"/>
                        <label for="pria">Pria</label>
                    </td>
                    <td>
                        <input type="radio" name="jnsklmn" id="wanita"/>
                        <label for="wanita">Wanita</label>
                    </td>
                </tr>
                <tr>
                    <td colspan="2">Hobi Anda (Pilih Satu atau lebih)</td>
                </tr>
                <tr>
                    <td>
                        <input type="checkbox" id="mainbola">
                        <label for="mainbola">Main Bola</label>
                    </td>
                    <td>
                        <input type="checkbox" id="coding">
                        <label for="coding">Coding</label>
                    </td>
                </tr>
                <tr>
                    <td colspan="2">Hewan Kesukaan Anda</td>
                </tr>
                <tr>
                    <td>Hewan :</td>
                    <td>
                        <select>
                            <option>Pilih hewan</option>
                            <option value="1">Tikus Berdasi</option>
                            <option value="2">Banteng Merah</option>
                            <option value="3">Tikus bau tenguk</option>
                        </select>
                    </td>
                </tr>
                <tr>
                    <td colspan="2">
                        <textarea placeholder="Isi teks apapun"></textarea>
                    </td>
                </tr>
                <tr>
                    <td>
                        <button type="submit">Kirim</button>
                    </td>
                    <td>
                        <button type="reset">Ulangi</button>
                    </td>
                </tr>
            </table>
        </form><br>
        <h2 id="teks_pertama">Ini adalah sebuah teks pertama</h2>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Provident voluptatum, minus non itaque repudiandae perferendis. Reprehenderit aperiam esse quia error facilis. Eius iure sequi, porro suscipit voluptatum in laborum unde.</p>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Eum, vel excepturi exercitationem quod accusamus eos laborum aliquid aperiam fuga atque saepe, cupiditate at explicabo! Neque quos quisquam architecto cum nihil!</p>
        <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Nobis odit tempore repudiandae ipsa tenetur corrupti dolor nisi aliquam sed labore dolores dolorum temporibus iusto maiores, harum iure officiis itaque quasi!</p><br>
        <h2 id="teks_kedua">Ini adalah sebuah teks kedua</h2>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Sit assumenda ipsa cupiditate ex fuga consectetur voluptates ipsum, repellat veniam tempore delectus nulla nostrum hic quis modi aperiam ab veritatis? Obcaecati.</p>
        <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Excepturi nesciunt temporibus iste porro, ipsam recusandae aut aperiam at id nam deleniti neque rem molestias possimus repellat atque saepe ad dolor?</p>
        <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Tenetur dolorum consequatur veritatis esse non, libero enim earum porro iste fugit eos quos. Quisquam cumque possimus, expedita consequuntur amet tenetur officiis.</p>
        <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Natus, ipsum aut cumque exercitationem dolor quos aspernatur atque ullam blanditiis earum officiis dolore porro nisi facere velit, quas eveniet nostrum sunt?</p><br><br><br>
    </body>
</html>
