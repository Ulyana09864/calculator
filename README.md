# calculator
<html>
<head>
    <meta charset="utf-8" />
    <title>JS</title>
</head>
<body>
    <div style="display:inline-block;">
        <form>
            <input type="text" id="a1" value="10" size="6"/>
            <select size="1" name="oper" style="width:150px;">
                <option>Выберите действие</option>
                <option value="+">+</option>
                <option value="-">-</option>
                <option value="*">*</option>
                <option value="/">/</option>
            </select>
            <input type="text" id="b1" value="2" size="6"/>
            <input type="button" value="Расчитать" onclick="a()" />
        </form>
    </div>
    <div>        
        <p> Ответ =</p><p>
            <textarea сols="20" rows="1" id="count" ></textarea>
        </p>
    </div>
</body>
</html>
