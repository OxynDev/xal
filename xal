def xal_encrypt(_0x4a9181):
    _0x13002f = "\u00030é\u00087°\u0094\u000e-³x\u009dûËfîâÀ\u000eZâ©\u0004\u009cSÑä`\u0088\u009cÁ'"
    global _0x103e4a, _0x1ea42a
    _0x1ea42a = ''
    _0x103e4a = 0
    x = _0x4a9181.count("") - 1
    while _0x103e4a < x:
        xx = ord(_0x4a9181[_0x103e4a])
        xxx = xx ^ ord(_0x13002f[_0x103e4a % len(_0x13002f)])
        xc = str(hex(255 & xxx)).replace("0x","")
        if len(xc) == 1:
            xc = "0" + xc
        _0x1ea42a = _0x1ea42a + xc
        _0x103e4a = _0x103e4a + 1
    return _0x1ea42a

def hex_to_string(hex):
    if hex[:2] == '0x':
        hex = hex[2:]
    string_value = bytes.fromhex(hex).decode('utf-8')
    return string_value


def xal_decrypt(_0x4a9181):
    global _0x103e4a, _0x1ea42a, new_0x4a9181
    new_0x4a9181 = _0x4a9181
    _0x1ea42a = ''
    _0x103e4a = 0
    _0x13002f = "\u00030é\u00087°\u0094\u000e-³x\u009dûËfîâÀ\u000eZâ©\u0004\u009cSÑä`\u0088\u009cÁ'"
    x = _0x4a9181.count("") - 1
    while _0x103e4a < x:
        try:
            string = new_0x4a9181[0] + new_0x4a9181[1]
            new_0x4a9181 = new_0x4a9181[2:]
            xx = int(string, 16)
            xxx = ord(_0x13002f[_0x103e4a % len(_0x13002f)]) ^ xx
            _0x1ea42a = _0x1ea42a + chr(xxx)
            _0x103e4a = _0x103e4a + 1
        except:
            break
    return _0x1ea42a
