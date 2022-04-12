PW = gg.prompt({'🔒 Input password: '},{[1]=''},{[1]='Zark Mod'})
if not PW then return
end 
if PW[1] == "" then gg.alert("😡Zark Mod😡") os.exit() end
if PW[1] =="0069" then 
 gg.toast('CREDIT Kill Hack Mod s')
else 
 gg.alert("Senha Incorreta") return end
gg.alert("Zark Mod Menu")
local loadcode = false
local loadcod = false
local loadcodd = false
function split(szFullString, szSeparator)
local nFindStartIndex = 1 
local nSplitIndex = 1 
local nSplitArray = {} while true do 
local 
nFindLastIndex = string.find(szFullString, szSeparator, nFindStartIndex) 
if not nFindLastIndex then 
nSplitArray[nSplitIndex] = string.sub(szFullString, nFindStartIndex, string.len(szFullString)) 
break end 
nSplitArray[nSplitIndex] = string.sub(szFullString, nFindStartIndex, nFindLastIndex - 1) 
nFindStartIndex = nFindLastIndex + string.len(szSeparator) 
nSplitIndex = nSplitIndex + 1 end return 
nSplitArray end function 
xgxc(szpy, qmxg) for x = 1, #(qmxg) do 
xgpy = szpy + qmxg[x]["offset"] xglx = qmxg[x]["type"] 
xgsz = qmxg[x]["value"] 
gg.setValues({[1] = {address = xgpy, flags = xglx, value = xgsz}}) 
xgsl = xgsl + 1 end end function 
xqmnb(qmnb) 
gg.clearResults() 
gg.setRanges(qmnb[1]["memory"]) 
gg.searchNumber(qmnb[3]["value"], qmnb[3]["type"]) 
if gg.getResultCount() == 0 then 
gg.toast(qmnb[2]["name"] .. "🇮🇳")
else 
gg.refineNumber(qmnb[3]["value"], qmnb[3]["type"]) 
gg.refineNumber(qmnb[3]["value"], qmnb[3]["type"]) 
gg.refineNumber(qmnb[3]["value"], qmnb[3]["type"]) 
if gg.getResultCount() == 0 then 
gg.toast(qmnb[2]["name"] .. "🇮🇳") 
else 
sl = gg.getResults(999999) 
sz = gg.getResultCount() 
xgsl = 0 if sz > 999999 then 
sz = 999999 end for i = 1, sz do 
pdsz = true for v = 4, #(qmnb) do if 
pdsz == true then 
pysz = {} pysz[1] = {} pysz[1].address = sl[i].address + qmnb[v]["offset"] 
pysz[1].flags = qmnb[v]["type"] 
szpy = gg.getValues(pysz) 
pdpd = qmnb[v]["lv"] .. ";" .. szpy[1].value szpd = split(pdpd, ";") 
tzszpd = szpd[1] 
pyszpd = szpd[2] 
if tzszpd == pyszpd then 
pdjg = true pdsz = true else 
pdjg = false pdsz = false end end end 
if pdjg == true then 
szpy = sl[i].address xgxc(szpy, qmxg) 
xgjg = true end end 
if xgjg == true then 
gg.toast(qmnb[2]["name"] .. "🇮🇳" .. xgsl .. "🇮🇳") 
else 
gg.toast(qmnb[2]["name"] .. "🇮🇳") 
end 
end 
end 
end
function SearchWrite(Search, Write, Type) gg.clearResults() gg.setVisible(false) gg.searchNumber(Search[1][1], Type) local count = gg.getResultCount() local result = gg.getResults(count) gg.clearResults() local data = {} local base = Search[1][2] if (count > 0) then for i, v in ipairs(result) do v.isUseful = true end  for k=2, #Search do local tmp = {} local offset = Search[k][2] - base local num = Search[k][1] for i, v in ipairs(result) do tmp[#tmp+1] = {} tmp[#tmp].address = v.address + offset tmp[#tmp].flags = v.flags end tmp = gg.getValues(tmp) for i, v in ipairs(tmp) do if ( tostring(v.value) ~= tostring(num) ) then result[i].isUseful = false end end end for i, v in ipairs(result) do if (v.isUseful) then data[#data+1] = v.address end end if (#data > 0) then gg.toast("🇮🇳"..#data.."🇮🇳") local t = {} local base = Search[1][2] for i=1, #data do for k, w in ipairs(Write) do offset = w[2] - base t[#t+1] = {} t[#t].address = data[i] + offset t[#t].flags = Type t[#t].value = w[1] if (w[3] == true) then local item = {} item[#item+1] = t[#t] item[#item].freeze = true gg.addListItems(item) end end end gg.setValues(t) else gg.toast("🇮🇳", false) return false end else gg.toast("🇮🇳") return false end end
os["remove"]("/storage/emulated/0/Android/data/com.herogame.gplay.lastdayrulessurvival/files/hero_log.txt")
os["remove"]("/storage/emulated/0/Android/imei")
if gg.isPackageInstalled("sstool.only.com.sstool") then
  print("Uninstall SSTOOL Deceypt")
  os.exit()
end
if gg.isPackageInstalled("sstool.only.com.sstool") then
  print("Uninstall SSTOOL Deceypt")
  os.exit()
end
if gg.isPackageInstalled("catch_.me_.if_.you_.can_") then
  print("Uninstall orginal GG")
  os.exit()
end
if gg.isPackageInstalled("com.guoshi.httpcanary") then
gg.alert("⛔ ᴜɴɪɴsᴛᴀʟʟ ʜᴛᴛᴘ ᴄᴀɴᴀʀʏ⛔")
os.exit()
end
if gg.isPackageInstalled("com.hckeam.mjgql") then
gg.alert("⛔ ᴜɴɪɴsᴛᴀʟʟ DEGG⛔")
os.exit()
end
----------------------
function ATT()
SN = gg.choice({
"👤┣ Função visual ●",
"⚔️┣ Função PvP ●",
"👑┣ Função especial ●",
"🏗️┣ Função especial ●",
"🚫┣ Ban report ●",
"SAIR",
}, nil,"┣【ZARK MOD】┫")
if SN == 1 then AT() end
if SN == 2 then AT1() end
if SN == 3 then AT2() end
if SN == 4 then AT3() end
if SN == 5 then AT4() end
if SN == 6 then SAIR() end
  XGCK = -1
end
function AT()
SN1 = gg.choice({
"📡┣ Antena de Cabeça ●",
"👁️┣ Ver Através das Paredes ●",
"🤺┣ Boneco branco ●",
"🌿┣ Remoção de grama ●",
"🔎┣ Vista distante ●",
"🤾┣ Salto em altura ●",
"Voltar",
}, nil,"┣【 Zark Mod 】┫")
if SN1 == 1 then
V1()
end
if SN1 == 2 then
V2()
end
if SN1 == 3 then
V3()
end
if SN1 == 4 then
V4()
end
if SN1 == 5 then
V5()
end
if SN1 == 6 then
V6()
end
if SN1 == 7 then
HOME()
end
XGCK = -1
end
function AT1()
SN2 = gg.choice({
"🔎┣ Mira 5x/10x ●",
"〰️ ┣ Sem recuo ●",
"⚡┣ Velocidade de Fogo ●",
"🔄┣ Recarregar Rapida ●",
"💢┣ Aim Lock ●",
"➖┣ Reduza o Dedilhado ●",
"↕️ ┣ Luffy ●",
"Voltar",
}, nil,"┣【 Zark Mod 】┫")
if SN2 == 1 then
D1()
end
if SN2 == 2 then
D2()
end
if SN2 == 3 then
D3()
end
if SN2 == 4 then
D4()
end
if SN2 == 5 then
D5()
end
if SN2 == 6 then
D6()
end
if SN2 == 7 then
D7()
end
if SN2 == 8 then
HOME()
end
XGCK = -1
end
function AT2()
SN3 = gg.choice({
"✝️┣ Bala Mágica ●",
"👃┣ Zombies Invisíveis ●",
"🗿┣ Andando Pela Textura ●",
"⚡┣ Correr Rapido ●",
"🏃┣ Salto ●",
"🗡️┣ Velocidade de impacto + alta velocidade ●",
"Voltar♥",
}, nil,"┣【 Zark Mod 】┫")
if SN3 == 1 then
H1()
end
if SN3 == 2 then
H2()
end
if SN3 == 3 then
H3()
end
if SN3 == 4 then
H4()
end
if SN3 == 5 then
H5()
end
if SN3 == 6 then
H6()
end
if SN3 == 7 then
HOME()
end
XGCK = -1
end
function AT3()
SN4 = gg.choice({
"🤽┣ Andar na Água ●",
"🌲┣ Remover Árvore ●",
"🕋┣ Construção subterrânea ●",
"🌗┣ Dia / Noite ●",
"Voltar",
}, nil,"┣【 Zark Mod 】┫")
if SN4 == 1 then
G1()
end
if SN4 == 2 then
G2()
end
if SN4 == 3 then
G3()
end
if SN4 == 4 then
G4()
end
if SN4 == 5 then
HOME()
end
XGCK = -1
end
function V1()
gg.clearResults()
gg.setRanges(32)
gg.searchNumber('0.16947640479', gg.REGION_C_BSS, false, gg.SIGN_FUZZY_EQUAL, 0, -1)
gg.getResults(999)
gg.editAll('-9999.0123', gg.REGION_C_BSS)
gg.clearResults()
gg.setRanges(32)
gg.searchNumber(-0.9855342507362366,16,false,536870912,0,-1)
gg.getResults(999)
gg.editAll(-999.0123,16)
gg.clearResults()
end
function V2()
gg.clearResults()
gg.setRanges(gg.REGION_VIDEO)
gg.setVisible(false)
gg.searchNumber("5.127597087642792E-29", gg.TYPE_FLOAT)
gg.getResults(9)
gg.editAll("5.127597087642792E29", gg.TYPE_FLOAT)
gg.clearResults()
end
function V3()
F = gg.alert('Olhe para o caractere branco (ajuste os gráficos do meio)', 'todo branco', 'Desligado', 'branco sem olhos ardentes')
  if F == 1 then
qmnb = {
{["memory"] = 32},
{["name"] = "เปิด"},
{["value"] = 82.5, ["type"] = 16},
{["lv"] = 15.0, ["offset"] = 4, ["type"] = 16},
{["lv"] = 5.0, ["offset"] = 12, ["type"] = 16},
{["lv"] = 0.75, ["offset"] = 1316, ["type"] = 16},
}
qmxg = {
{["value"] = 20.0123456789, ["offset"] = 1316, ["type"] = 16},
}
xqmnb(qmnb)
gg.clearResults()
elseif F == 2 then
gg.clearResults()
gg.setRanges(32)
gg.searchNumber("20.0123456789", gg.TYPE_FLOAT)
gg.getResults(900)
gg.editAll("0.75", gg.TYPE_FLOAT)
gg.clearResults()
elseif F == 3 then 
qmnb = {
{memory = 1048576},
{name = ""},
{value = "0.040008544921875",type = 16},
{lv = "0.9599609375",offset = -8,type = 16}}
qmxg = {
{value = 120,offset = -8,type = 16}}
xqmnb(qmnb)
gg.clearList()
gg.clearResults()
gg.setRanges(1048576)
gg.searchNumber("16.0;3.0;2.0::52", 16, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("2", 16, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(999)
gg.editAll("999", 16)
end
end
function V4()
F = gg["alert"]("Remova a grama, remova as árvores, ajuste os gráficos de sombra ao mínimo", "V2", "Desligado", "V1")
if F == 1 then
gg["clearResults"]()
gg["setRanges"](gg.REGION_VIDEO)
gg["searchNumber"]("2.37555122375", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg["getResults"](999)
gg["editAll"]("0.0000001234", 16)
gg["clearResults"]()
gg["setRanges"](gg.REGION_VIDEO)
gg["searchNumber"]("3.96402846e-29", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg["getResults"](999)
gg["editAll"]("0.000000123", 16)
elseif F == 2 then
gg["clearResults"]()
gg["setRanges"](gg.REGION_VIDEO)
gg["searchNumber"]("0.00000121", gg.TYPE_FLOAT, false, gg.SIGN_FUZZY_EQUAL, 0, -1)
gg["getResults"](999)
gg["editAll"]("2.37554955482", 16)
gg["clearResults"]()
gg["clearResults"]()
gg["setRanges"](gg.REGION_VIDEO)
gg["searchNumber"]("0.00000122", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg["getResults"](999)
gg["editAll"]("3.94430543e-29", gg.TYPE_FLOAT)
gg["clearResults"]()
gg["setRanges"](gg.REGION_VIDEO)
gg["searchNumber"]("0.0000001234", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg["getResults"](999)
gg["editAll"]("2.37555122375", 16)
gg["clearResults"]()
gg["clearResults"]()
gg["setRanges"](gg.REGION_VIDEO)
gg["searchNumber"]("0.000000123", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg["getResults"](999)
gg["editAll"]("3.96402846e-29", 16)
elseif F == 3 then
gg["clearResults"]()
gg["setRanges"](gg.REGION_VIDEO)
gg["searchNumber"]("2.37554955482", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg["getResults"](999)
gg["editAll"]("0.00000121", 16)
gg["clearResults"]()
gg["setRanges"](gg.REGION_VIDEO)
gg["searchNumber"]("3.94430543e-29", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg["getResults"](999)
gg["editAll"]("0.00000122", 16)
gg["clearResults"]()
end
end
function V5()
ml = gg.prompt({
"🕴️Visualizar personalização🕴️ [-5;20] "
}, {1.5}, {"number"})
if ml == nil then
do return end
return
end
if loadcod == false then
gg.clearResults()
gg.setRanges(32)
gg.searchNumber("1.70000004768", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("1.70000004768", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.addListItems((gg.getResults(10000)))
gg.saveList(gg.EXT_STORAGE .. "/./fuck.txt", 0)
gg.clearResults()
gg.clearList()
loadcod = true
end
gg.loadList(gg.EXT_STORAGE .. "/./fuck.txt", 0)
a = gg.getListItems()
gg.loadResults(a)
gg.removeListItems(a)
g = gg.getResults(10000)
gg.editAll(ml[1], 16)
end
function V6()
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("-3.86857323e25;1;1.00999999046", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("1", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(10)
gg.editAll("0.1", gg.TYPE_FLOAT)
gg.toast("")
gg.clearResults()
gg.setRanges(gg.REGION_ANONYMOUS)
gg.searchNumber("16,256W;1.03~1.042F;16,261W;-26,214W;15,897W::", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("1.03~1.042", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.getResults(100)
gg.getResultCount()
gg.toast("")
gg.setVisible(false)
end
function D1()
  F = gg.alert("Mira 5x/10x ", "Zoom10X", "Zoom5X")
  if F == 1 then
    gg.setRanges(32)
    SearchWrite({
      {1111490560, 6584},
      {0, 6588},
      {0, 6596}
    }, {
      {
        1084410514,
        6584,
        false
      }
    }, 4)
    gg.clearResults()
    gg.setRanges(32)
    SearchWrite({
      {1110704128, 36264},
      {0, 36256},
      {0, 36268}
    }, {
      {
        1084410514,
        36264,
        false
      }
    }, 4)
    gg.clearResults()
  elseif F == 2 then
    gg.setRanges(32)
    SearchWrite({
      {1111490560, 6584},
      {0, 6588},
      {0, 6596}
    }, {
      {
        1092616192,
        6584,
        false
      }
    }, 4)
    gg.clearResults()
    gg.setRanges(32)
    SearchWrite({
      {1110704128, 36264},
      {0, 36256},
      {0, 36268}
    }, {
      {
        1092616192,
        36264,
        false
      }
    }, 4)
    gg.clearResults()
  end
end
function D2()
SN5 = gg.choice({
"〰️┣ M4 ●",
"〰️┣ AK ●",
"〰️┣ QBZ ●",
"〰️┣ UZI ●",
"〰️┣ M762 ●",
"〰️┣ BAZUCA ●",
"〰️┣ SMG ●",
"〰️┣ FAMAS ●",
"〰️┣ MG4 ●",
"〰️┣ LEWIS ●",
"〰️┣ PISTOLA PRETA ●",
"〰️┣ SNIPER ●",
"〰️┣ ESCOPETA ●",
"〰️┣ CLASSE ●",
"Voltar",
}, nil,"┣【 Zark Mod 】┫")
if SN5 == 1 then
M4()
end
if SN5 == 2 then
AK()
end
if SN5 == 3 then
QBZ()
end
if SN5 == 4 then
UZI()
end
if SN5 == 5 then
M762()
end
if SN5== 6 then
BAZUCA()
end
if SN5 == 7 then
SMG()
end
if SN5 == 8 then
FAMAS()
end
if SN5 == 9 then
MG4()
end
if SN5 == 10 then
LEWIS()
end
if SN5 == 11 then
PISTOLA()
end
if SN5 == 12 then
SNIPER()
end
if SN5 == 13 then
ESCOPETA()
end
if SN5 == 14 then
CLASSE()
end
if SN5 == 15 then
HOME()
end
XGCK = -1
end
function M4()
qmnb = {
{["memory"] = 32},
{["name"] = "Mod Arma"},
{["value"] = 830.0, ["type"] = 16},
{["lv"] = 12.0, ["offset"] = -148, ["type"] = 16},
{["lv"] = 24.0, ["offset"] = -144, ["type"] = 16},
{["lv"] = 45.0, ["offset"] = -140, ["type"] = 16},
{["lv"] = 3.5, ["offset"] = -124, ["type"] = 16},
{["lv"] = 4.0, ["offset"] = 16, ["type"] = 16},
{["lv"] = 4.0, ["offset"] = 24, ["type"] = 16},
}
qmxg = {
{["value"] = 99999, ["offset"] = 0, ["type"] = 16},
{["value"] = 0, ["offset"] = -148, ["type"] = 16},
{["value"] = 0, ["offset"] = -144, ["type"] = 16},
{["value"] = 0, ["offset"] = -140, ["type"] = 16},
{["value"] = 0, ["offset"] = -124, ["type"] = 16},
{["value"] = 0, ["offset"] = 16, ["type"] = 16},
{["value"] = 0, ["offset"] = 24, ["type"] = 16},
}
xqmnb(qmnb)
end
function AK()
qmnb = {
{["memory"] = 32},
{["name"] = "Mod Arma"},
{["value"] = 735.0, ["type"] = 16},
{["lv"] = 50.0, ["offset"] = -140, ["type"] = 16},
}
qmxg = {
{["value"] = 99999, ["offset"] = 0, ["type"] = 16},
{["value"] = 0, ["offset"] = -148, ["type"] = 16},
{["value"] = 0, ["offset"] = -144, ["type"] = 16},
{["value"] = 0, ["offset"] = -140, ["type"] = 16},
{["value"] = 0, ["offset"] = -124, ["type"] = 16},
{["value"] = 0, ["offset"] = 16, ["type"] = 16},
{["value"] = 0, ["offset"] = 24, ["type"] = 16},
}
xqmnb(qmnb)
end
function QBZ()
qmnb = {
{["memory"] = 32},
{["name"] = "Mod Arma"},
{["value"] = 790.0, ["type"] = 16},
{["lv"] = 12.0, ["offset"] = -148, ["type"] = 16},
{["lv"] = 27.0, ["offset"] = -144, ["type"] = 16},
{["lv"] = 45.0, ["offset"] = -140, ["type"] = 16},
{["lv"] = 3.5, ["offset"] = -124, ["type"] = 16},
{["lv"] = 4.0, ["offset"] = 16, ["type"] = 16},
{["lv"] = 4.0, ["offset"] = 24, ["type"] = 16},
}
qmxg = {
{["value"] = 99999, ["offset"] = 0, ["type"] = 16},
{["value"] = 0, ["offset"] = -148, ["type"] = 16},
{["value"] = 0, ["offset"] = -144, ["type"] = 16},
{["value"] = 0, ["offset"] = -140, ["type"] = 16},
{["value"] = 0, ["offset"] = -124, ["type"] = 16},
{["value"] = 0, ["offset"] = 16, ["type"] = 16},
{["value"] = 0, ["offset"] = 24, ["type"] = 16},
}
xqmnb(qmnb)
end
function UZI()
qmnb = {
{["memory"] = 32},
{["name"] = "Mod Arma"},
{["value"] = 320.0, ["type"] = 16},
{["lv"] = 16.0, ["offset"] = -148, ["type"] = 16},
{["lv"] = 34.0, ["offset"] = -144, ["type"] = 16},
{["lv"] = 42.0, ["offset"] = -140, ["type"] = 16},
{["lv"] = 3.0, ["offset"] = -124, ["type"] = 16},
{["lv"] = 4.0, ["offset"] = 16, ["type"] = 16},
{["lv"] = 4.0, ["offset"] = 24, ["type"] = 16},
}
qmxg = {
{["value"] = 99999, ["offset"] = 0, ["type"] = 16},
{["value"] = 0, ["offset"] = -148, ["type"] = 16},
{["value"] = 0, ["offset"] = -144, ["type"] = 16},
{["value"] = 0, ["offset"] = -140, ["type"] = 16},
{["value"] = 0, ["offset"] = -124, ["type"] = 16},
{["value"] = 0, ["offset"] = 16, ["type"] = 16},
{["value"] = 0, ["offset"] = 24, ["type"] = 16},
}
xqmnb(qmnb)
end
function M762()
qmnb = {
{["memory"] = 32},
{["name"] = "Mod Arma"},
{["value"] = 735.0, ["type"] = 16},
{["lv"] = 50.0, ["offset"] = -140, ["type"] = 16},
}
qmxg = {
{["value"] = 99999, ["offset"] = 0, ["type"] = 16},
{["value"] = 0, ["offset"] = -148, ["type"] = 16},
{["value"] = 0, ["offset"] = -144, ["type"] = 16},
{["value"] = 0, ["offset"] = -140, ["type"] = 16},
{["value"] = 0, ["offset"] = -124, ["type"] = 16},
{["value"] = 0, ["offset"] = 16, ["type"] = 16},
{["value"] = 0, ["offset"] = 24, ["type"] = 16},
}
xqmnb(qmnb)
end
function BAZUCA()
qmnb = {
{["memory"] = 32},
{["name"] = "Mod Arma"},
{["value"] = 278.0, ["type"] = 16},
{["lv"] = 15.0, ["offset"] = -196, ["type"] = 16},
{["lv"] = 30.0, ["offset"] = -192, ["type"] = 16},
{["lv"] = 45.0, ["offset"] = -188, ["type"] = 16},
{["lv"] = 35.0, ["offset"] = -172, ["type"] = 16},
{["lv"] = 4.0, ["offset"] = -84, ["type"] = 16},
{["lv"] = 4.0, ["offset"] = -80, ["type"] = 16},
{["lv"] = 40.0, ["offset"] = -48, ["type"] = 16},
{["lv"] = 20.0, ["offset"] = -32, ["type"] = 16},
{["lv"] = 10.0, ["offset"] = -24, ["type"] = 16},
}
qmxg = {
{["value"] = 0, ["offset"] = -196, ["type"] = 16},
{["value"] = 0, ["offset"] = -192, ["type"] = 16},
{["value"] = 0, ["offset"] = -188, ["type"] = 16},
{["value"] = 0, ["offset"] = -172, ["type"] = 16},
{["value"] = 0, ["offset"] = -84, ["type"] = 16},
{["value"] = 0, ["offset"] = -80, ["type"] = 16},
{["value"] = 99999, ["offset"] = -48, ["type"] = 16},
{["value"] = 0, ["offset"] = -32, ["type"] = 16},
{["value"] = 0, ["offset"] = -24, ["type"] = 16},
}
xqmnb(qmnb)

qmnb = {
{["memory"] = 32},
{["name"] = "Mod Arma"},
{["value"] = 400.0, ["type"] = 16},
{["lv"] = 24.0, ["offset"] = -188, ["type"] = 16},
{["lv"] = 24.0, ["offset"] = -184, ["type"] = 16},
{["lv"] = 24.0, ["offset"] = -180, ["type"] = 16},
{["lv"] = 35.0, ["offset"] = -164, ["type"] = 16},
{["lv"] = 4.0, ["offset"] = -76, ["type"] = 16},
{["lv"] = 4.0, ["offset"] = -72, ["type"] = 16},
{["lv"] = 25.0, ["offset"] = -40, ["type"] = 16},
{["lv"] = 20.0, ["offset"] = -24, ["type"] = 16},
{["lv"] = 10.0, ["offset"] = -12, ["type"] = 16},
}
qmxg = {
{["value"] = 0, ["offset"] = -188, ["type"] = 16},
{["value"] = 0, ["offset"] = -184, ["type"] = 16},
{["value"] = 0, ["offset"] = -180, ["type"] = 16},
{["value"] = 0, ["offset"] = -164, ["type"] = 16},
{["value"] = 0, ["offset"] = -76, ["type"] = 16},
{["value"] = 0, ["offset"] = -72, ["type"] = 16},
{["value"] = 99999, ["offset"] = -40, ["type"] = 16},
{["value"] = 0, ["offset"] = -24, ["type"] = 16},
{["value"] = 0, ["offset"] = -12, ["type"] = 16},
}
xqmnb(qmnb)
end
function SMG()
qmnb = {
{["memory"] = 32},
{["name"] = "Mod Arma"},
{["value"] = 300.0, ["type"] = 16},
{["lv"] = 15.0, ["offset"] = -148, ["type"] = 16},
{["lv"] = 32.0, ["offset"] = -144, ["type"] = 16},
{["lv"] = 44.0, ["offset"] = -140, ["type"] = 16},
{["lv"] = 2.5, ["offset"] = -124, ["type"] = 16},
{["lv"] = 4.0, ["offset"] = 16, ["type"] = 16},
{["lv"] = 4.0, ["offset"] = 24, ["type"] = 16},
}
qmxg = {
{["value"] = 99999, ["offset"] = 0, ["type"] = 16},
{["value"] = 0, ["offset"] = -148, ["type"] = 16},
{["value"] = 0, ["offset"] = -144, ["type"] = 16},
{["value"] = 0, ["offset"] = -140, ["type"] = 16},
{["value"] = 0, ["offset"] = -124, ["type"] = 16},
{["value"] = 0, ["offset"] = 16, ["type"] = 16},
{["value"] = 0, ["offset"] = 24, ["type"] = 16},
}
xqmnb(qmnb)
end
function FAMAS()
qmnb = {
{["memory"] = 32},
{["name"] = "Mod Arma"},
{["value"] = 360.0, ["type"] = 16},
{["lv"] = 14.0, ["offset"] = -148, ["type"] = 16},
{["lv"] = 30.0, ["offset"] = -144, ["type"] = 16},
{["lv"] = 42.0, ["offset"] = -140, ["type"] = 16},
{["lv"] = 2.5, ["offset"] = -124, ["type"] = 16},
{["lv"] = 4.0, ["offset"] = 16, ["type"] = 16},
{["lv"] = 4.0, ["offset"] = 24, ["type"] = 16},
}
qmxg = {
{["value"] = 99999, ["offset"] = 0, ["type"] = 16},
{["value"] = 0, ["offset"] = -148, ["type"] = 16},
{["value"] = 0, ["offset"] = -144, ["type"] = 16},
{["value"] = 0, ["offset"] = -140, ["type"] = 16},
{["value"] = 0, ["offset"] = -124, ["type"] = 16},
{["value"] = 0, ["offset"] = 16, ["type"] = 16},
{["value"] = 0, ["offset"] = 24, ["type"] = 16},
}
xqmnb(qmnb)
end
function MG4()
qmnb = {
{["memory"] = 32},
{["name"] = "Mod Arma"},
{["value"] = 480.0, ["type"] = 16},
{["lv"] = 20.0, ["offset"] = -148, ["type"] = 16},
{["lv"] = 40.0, ["offset"] = -144, ["type"] = 16},
{["lv"] = 55.0, ["offset"] = -140, ["type"] = 16},
{["lv"] = 10.0, ["offset"] = -124, ["type"] = 16},
{["lv"] = 7.0, ["offset"] = 16, ["type"] = 16},
{["lv"] = 10.0, ["offset"] = 24, ["type"] = 16},
}
qmxg = {
{["value"] = 99999, ["offset"] = 0, ["type"] = 16},
{["value"] = 0, ["offset"] = -148, ["type"] = 16},
{["value"] = 0, ["offset"] = -144, ["type"] = 16},
{["value"] = 0, ["offset"] = -140, ["type"] = 16},
{["value"] = 0, ["offset"] = -124, ["type"] = 16},
{["value"] = 0, ["offset"] = 16, ["type"] = 16},
{["value"] = 0, ["offset"] = 24, ["type"] = 16},
}
xqmnb(qmnb)
end
function LEWIS()
qmnb = {
 {memory = 32},
    {
      name = "Mod Arma"
    },
    {value = "480.0", type = 16},
    {lv = "20.0",offset = -148,type = 16},
    {lv = "40.0",offset = -144,type = 16},
    {lv = "6.0",offset = -136,type = 16},
    {lv = "60.0",offset = -120,type = 16},
    {lv = "0.5",offset = -100,type = 16},
    {lv = "4.0",offset = 16,type = 16},
    {lv = "4.0",offset = 24,type = 16},
    {lv = "1.0",offset = 160,type = 16}}
  qmxg = {
 {value = 0,offset = -148,type = 16},
    {value = 0,offset = -144,type = 16},
    {value = 0,offset = -136,type = 16},
    {value = 0,offset = -120,type = 16},
    {value = 0,offset = -100,type = 16},
    {value = 99999,offset = 0,type = 16},
    {value = 0,offset = 16,type = 16},
    {value = 0,offset = 24,type = 16},
    {value = 0,offset = 160,type = 16}}
xqmnb(qmnb)
end
function PISTOLA()
qmnb = {
{["memory"] = 32},
{["name"] = "Mod Arma"},
{["value"] = 300.0, ["type"] = 16},
{["lv"] = 15.0, ["offset"] = -148, ["type"] = 16},
{["lv"] = 30.0, ["offset"] = -144, ["type"] = 16},
{["lv"] = 50.0, ["offset"] = -140, ["type"] = 16},
{["lv"] = 5.0, ["offset"] = -124, ["type"] = 16},
{["lv"] = 5.0, ["offset"] = 16, ["type"] = 16},
{["lv"] = 9.0, ["offset"] = 24, ["type"] = 16},
}
qmxg = {
{["value"] = 0, ["offset"] = 0, ["type"] = 16},
{["value"] = 0, ["offset"] = -148, ["type"] = 16},
{["value"] = 0, ["offset"] = -144, ["type"] = 16},
{["value"] = 0, ["offset"] = -140, ["type"] = 16},
{["value"] = 0, ["offset"] = -124, ["type"] = 16},
{["value"] = 0, ["offset"] = 16, ["type"] = 16},
{["value"] = 0, ["offset"] = 24, ["type"] = 16},
}
xqmnb(qmnb)

qmnb = {
{["memory"] = 32},
{["name"] = ""},
{["value"] = 300.0, ["type"] = 16},
{["lv"] = 15.0, ["offset"] = -148, ["type"] = 16},
{["lv"] = 30.0, ["offset"] = -144, ["type"] = 16},
{["lv"] = 50.0, ["offset"] = -140, ["type"] = 16},
{["lv"] = 5.0, ["offset"] = -124, ["type"] = 16},
{["lv"] = 5.0, ["offset"] = 16, ["type"] = 16},
{["lv"] = 9.0, ["offset"] = 24, ["type"] = 16},
}
qmxg = {
{["value"] = 99999, ["offset"] = 0, ["type"] = 16},
{["value"] = 0, ["offset"] = -148, ["type"] = 16},
{["value"] = 0, ["offset"] = -144, ["type"] = 16},
{["value"] = 0, ["offset"] = -140, ["type"] = 16},
{["value"] = 0, ["offset"] = -124, ["type"] = 16},
{["value"] = 0, ["offset"] = 16, ["type"] = 16},
{["value"] = 0, ["offset"] = 24, ["type"] = 16},
}
xqmnb(qmnb)
end
function SNIPER()
qmnb = {
{["memory"] = 32},
{["name"] = "Mod Arma"},
{["value"] = 480.0, ["type"] = 16},
{["lv"] = 20.0, ["offset"] = -148, ["type"] = 16},
{["lv"] = 40.0, ["offset"] = -144, ["type"] = 16},
{["lv"] = 55.0, ["offset"] = -140, ["type"] = 16},
{["lv"] = 10.0, ["offset"] = -124, ["type"] = 16},
{["lv"] = 7.0, ["offset"] = 16, ["type"] = 16},
{["lv"] = 10.0, ["offset"] = 24, ["type"] = 16},
}
qmxg = {
{["value"] = 99999, ["offset"] = 0, ["type"] = 16},
{["value"] = 0, ["offset"] = -148, ["type"] = 16},
{["value"] = 0, ["offset"] = -144, ["type"] = 16},
{["value"] = 0, ["offset"] = -140, ["type"] = 16},
{["value"] = 0, ["offset"] = -124, ["type"] = 16},
{["value"] = 0, ["offset"] = 16, ["type"] = 16},
{["value"] = 0, ["offset"] = 24, ["type"] = 16},
}
xqmnb(qmnb)
  
  qmnb = {
 {memory = 32},
    {
      name = "Mod Arma"
    },
    {value = "480.0", type = 16},
    {lv = "20.0",offset = -148,type = 16},
    {lv = "40.0",offset = -144,type = 16},
    {lv = "6.0",offset = -136,type = 16},
    {lv = "60.0",offset = -120,type = 16},
    {lv = "0.5",offset = -100,type = 16},
    {lv = "4.0",offset = 16,type = 16},
    {lv = "4.0",offset = 24,type = 16},
    {lv = "1.0",offset = 160,type = 16}}
  qmxg = {
 {value = 0,offset = -148,type = 16},
    {value = 0,offset = -144,type = 16},
    {value = 0,offset = -136,type = 16},
    {value = 0,offset = -120,type = 16},
    {value = 0,offset = -100,type = 16},
    {value = 99999,offset = 0,type = 16},
    {value = 0,offset = 16,type = 16},
    {value = 0,offset = 24,type = 16},
    {value = 0,offset = 160,type = 16}}

xqmnb(qmnb)

  qmnb = {
{["memory"] = 32},
{["name"] = "Mod Arma"},
{["value"] = 300.0, ["type"] = 16},
{["lv"] = 15.0, ["offset"] = -148, ["type"] = 16},
{["lv"] = 30.0, ["offset"] = -144, ["type"] = 16},
{["lv"] = 50.0, ["offset"] = -140, ["type"] = 16},
{["lv"] = 5.0, ["offset"] = -124, ["type"] = 16},
{["lv"] = 5.0, ["offset"] = 16, ["type"] = 16},
{["lv"] = 9.0, ["offset"] = 24, ["type"] = 16},
}
qmxg = {
{["value"] = 0, ["offset"] = 0, ["type"] = 16},
{["value"] = 0, ["offset"] = -148, ["type"] = 16},
{["value"] = 0, ["offset"] = -144, ["type"] = 16},
{["value"] = 0, ["offset"] = -140, ["type"] = 16},
{["value"] = 0, ["offset"] = -124, ["type"] = 16},
{["value"] = 0, ["offset"] = 16, ["type"] = 16},
{["value"] = 0, ["offset"] = 24, ["type"] = 16},
}
xqmnb(qmnb)

qmnb = {
{["memory"] = 32},
{["name"] = "Mod Arma"},
{["value"] = 300.0, ["type"] = 16},
{["lv"] = 15.0, ["offset"] = -148, ["type"] = 16},
{["lv"] = 30.0, ["offset"] = -144, ["type"] = 16},
{["lv"] = 50.0, ["offset"] = -140, ["type"] = 16},
{["lv"] = 5.0, ["offset"] = -124, ["type"] = 16},
{["lv"] = 5.0, ["offset"] = 16, ["type"] = 16},
{["lv"] = 9.0, ["offset"] = 24, ["type"] = 16},
}
qmxg = {
{["value"] = 99999, ["offset"] = 0, ["type"] = 16},
{["value"] = 0, ["offset"] = -148, ["type"] = 16},
{["value"] = 0, ["offset"] = -144, ["type"] = 16},
{["value"] = 0, ["offset"] = -140, ["type"] = 16},
{["value"] = 0, ["offset"] = -124, ["type"] = 16},
{["value"] = 0, ["offset"] = 16, ["type"] = 16},
{["value"] = 0, ["offset"] = 24, ["type"] = 16},
}
xqmnb(qmnb)
end
function ESCOPETA()
qmnb = {
 {memory = 32},
    {name = "Mod Arma"},
    {value = 45, type = 16},
    {lv = "3.0",offset = 12,type = 16},
    {lv = "60.0",offset = 28,type = 16},
    {lv = "300.0",offset = 148,type = 16},
    {lv = "13.0",offset = 164,type = 16},
    {lv = "8.0",offset = 192,type = 16}}
  qmxg = {
 {value = 0,offset = 0,type = 16},
    {value = 0,offset = 12,type = 16},
    {value = 0,offset = 28,type = 16},
    {value = 99999.011,offset = 148,type = 16},
    {value = 0,offset = 164,type = 16},
    {value = 0,offset = 192,type = 16}}
  xqmnb(qmnb)
  
  qmnb = {
 {memory = 32},
    {name = "Mod Arma"},
    {value = 45, type = 16},
    {lv = "3.0",offset = 12,type = 16},
    {lv = "60.0",offset = 28,type = 16},
    {lv = "300.0",offset = 148,type = 16},
    {lv = "15.0",offset = 164,type = 16},
    {lv = "8.0",offset = 192,type = 16}}
  qmxg = {
 {value = 0,offset = 0,type = 16},
    {value = 0,offset = 12,type = 16},
    {value = 0,offset = 28,type = 16},
    {value = 99999.012,offset = 148,type = 16},
    {value = 0,offset = 164,type = 16},
    {value = 0,offset = 192,type = 16}}
  xqmnb(qmnb)
end
function CLASSE()
SN6 = gg.choice({
"〰️┣RIFLE ●",
"〰️┣METRALHADORA ●",
"Back",
}, nil,"┣【Zark Mod】┫")
if SN6 == 1 then
RIFLE()
end
if SN6 == 2 then
METRALHADORA()
end
if SN6 == 3 then
HOME()
end
XGCK = -1
end
function RIFLE()
Q = gg.prompt({"◉Gun 🇮🇳 stillness◉ \n                         ╏Low streak╏                       ╏High streak╏ [0;40] ",   "◉Low streak◉ \n                  ╏Low streak╏                       ╏High streak╏ [0;4] ","◉Left-flip-right◉ \n                  ╏Low-flip╏                       ╏High-Flip╏ [0;4] "},{20,2,2},{"number","number","number"})
if Q == nil then return else
qmnb = {
{["memory"] = 32},
{["name"] = "[M4]"},
{["value"] = 830.0, ["type"] = 16},
{["lv"] = 45.0, ["offset"] = -140, ["type"] = 16},
}
qmxg = {
{["value"] = Q[1], ["offset"] = -148, ["type"] = 16},
{["value"] = Q[1], ["offset"] = -144, ["type"] = 16},
{["value"] = 0, ["offset"] = -124, ["type"] = 16},
{["value"] = Q[2], ["offset"] = 16, ["type"] = 16},
{["value"] = Q[3], ["offset"] = 24, ["type"] = 16},
}
xqmnb(qmnb)

qmnb = {
{["memory"] = 32},
{["name"] = "[QBZ]"},
{["value"] = 790.0, ["type"] = 16},
{["lv"] = 45.0, ["offset"] = -140, ["type"] = 16},
}
qmxg = {
{["value"] = Q[1], ["offset"] = -148, ["type"] = 16},
{["value"] = Q[1], ["offset"] = -144, ["type"] = 16},
{["value"] = 0, ["offset"] = -124, ["type"] = 16},
{["value"] = Q[2], ["offset"] = 16, ["type"] = 16},
{["value"] = Q[3], ["offset"] = 24, ["type"] = 16},
}
xqmnb(qmnb)

qmnb = {
{["memory"] = 32},
{["name"] = "[AK M762]"},
{["value"] = 735.0, ["type"] = 16},
{["lv"] = 50.0, ["offset"] = -140, ["type"] = 16},
}
qmxg = {
{["value"] = Q[1], ["offset"] = -148, ["type"] = 16},
{["value"] = Q[1], ["offset"] = -144, ["type"] = 16},
{["value"] = 0, ["offset"] = -124, ["type"] = 16},
{["value"] = Q[2], ["offset"] = 16, ["type"] = 16},
{["value"] = Q[3], ["offset"] = 24, ["type"] = 16},
}
xqmnb(qmnb)
end
end

function METRALHADORA()
Q = gg.prompt({"◉Gun stillness◉ \n ╏Low streak╏ ╏High streak╏ [0;40] ","◉Low streak◉ \n Low streak╏ ╏High streak╏ [  0;4] ","◉Left Flick Right◉ \n ╏Left Flick ╏High Flick ╏ [0;4] "},{20,2,2},{"number","number","number"})
if Q == nil then return else
qmnb = {
{["memory"] = 32},
{["name"] = "[SMG]"},
{["value"] = 300.0, ["type"] = 16},
{["lv"] = 44.0, ["offset"] = -140, ["type"] = 16},
}
qmxg = {
{["value"] = Q[1], ["offset"] = -148, ["type"] = 16},
{["value"] = Q[1], ["offset"] = -144, ["type"] = 16},
{["value"] = 0, ["offset"] = -124, ["type"] = 16},
{["value"] = Q[2], ["offset"] = 16, ["type"] = 16},
{["value"] = Q[3], ["offset"] = 24, ["type"] = 16},
}
xqmnb(qmnb)

qmnb = {
{["memory"] = 32},
{["name"] = "[UZI]"},
{["value"] = 320.0, ["type"] = 16},
{["lv"] = 42.0, ["offset"] = -140, ["type"] = 16},
}
qmxg = {
{["value"] = Q[1], ["offset"] = -148, ["type"] = 16},
{["value"] = Q[1], ["offset"] = -144, ["type"] = 16},
{["value"] = 0, ["offset"] = -124, ["type"] = 16},
{["value"] = Q[2], ["offset"] = 16, ["type"] = 16},
{["value"] = Q[3], ["offset"] = 24, ["type"] = 16},
}
xqmnb(qmnb)

qmnb = {
{["memory"] = 32},
{["name"] = "[Famas]"},
{["value"] = 360.0, ["type"] = 16},
{["lv"] = 42.0, ["offset"] = -140, ["type"] = 16},
}
qmxg = {
{["value"] = Q[1], ["offset"] = -148, ["type"] = 16},
{["value"] = Q[1], ["offset"] = -144, ["type"] = 16},
{["value"] = 0, ["offset"] = -124, ["type"] = 16},
{["value"] = Q[2], ["offset"] = 16, ["type"] = 16},
{["value"] = Q[3], ["offset"] = 24, ["type"] = 16},
}
xqmnb(qmnb)
end
end
function D3()
F = gg.alert("🇮🇳 Tiro Rápido 🇮🇳", "X8","DESLIGADO","X4")
    if F == 1 then
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_APP)
    gg.searchNumber("1.51061000005", 16,false,gg.SIGN_EQUAL,0, -1)
    gg.refineNumber("1.51061000005",16,false,gg.SIGN_EQUAL,0,-1)
    gg.getResults(1000)
    gg.editAll("0.00100000005",16)
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_APP)
    gg.searchNumber("0.00061000005", 16,false,gg.SIGN_EQUAL,0, -1)
    gg.refineNumber("0.00061000005",16,false,gg.SIGN_EQUAL,0,-1)
    gg.getResults(10000)
    gg.editAll("0.00100000005",16)
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_APP)
    gg.searchNumber("0.00100000005", 16,false,gg.SIGN_EQUAL,0, -1)
    gg.refineNumber("0.00100000005",16,false,gg.SIGN_EQUAL,0,-1)
    gg.getResults(1000)
    gg.editAll("0.00005120005",16)
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_SYS)
    gg.searchNumber("1.51061000005", 16,false,gg.SIGN_EQUAL,0, -1)
    gg.refineNumber("1.51061000005",16,false,gg.SIGN_EQUAL,0,-1)
    gg.getResults(1000)
    gg.editAll("0.00100000005",16)
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_SYS)
    gg.searchNumber("0.00061000005", 16,false,gg.SIGN_EQUAL,0, -1)
    gg.refineNumber("0.00061000005",16,false,gg.SIGN_EQUAL,0,-1)
    gg.getResults(10000)
    gg.editAll("0.00100000005",16)
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_SYS)
    gg.searchNumber("0.00100000005", 16,false,gg.SIGN_EQUAL,0, -1)
    gg.refineNumber("0.00100000005",16,false,gg.SIGN_EQUAL,0,-1)
    gg.getResults(1000)
    gg.editAll("0.00005120005",16)
    elseif F == 2 then
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_APP)
    gg.searchNumber("0.00061000005", 16,false,gg.SIGN_EQUAL,0, -1)
    gg.refineNumber("0.00061000005",16,false,gg.SIGN_EQUAL,0,-1)
    gg.getResults(10000)
    gg.editAll("0.00100000005",16)
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_APP)
    gg.searchNumber("0.00005120005", 16,false,gg.SIGN_EQUAL,0, -1)
    gg.refineNumber("0.00005120005",16,false,gg.SIGN_EQUAL,0,-1)
    gg.getResults(10000)
    gg.editAll("0.00100000005",16)
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_SYS)
    gg.searchNumber("0.00061000005", 16,false,gg.SIGN_EQUAL,0, -1)
    gg.refineNumber("0.00061000005",16,false,gg.SIGN_EQUAL,0,-1)
    gg.getResults(10000)
    gg.editAll("0.00100000005",16)
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_SYS)
    gg.searchNumber("0.00005120005", 16,false,gg.SIGN_EQUAL,0, -1)
    gg.refineNumber("0.00005120005",16,false,gg.SIGN_EQUAL,0,-1)
    gg.getResults(10000)
    gg.editAll("0.00100000005",16)
    elseif F == 3 then
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_APP)
    gg.searchNumber("0.00005120005", 16,false,gg.SIGN_EQUAL,0, -1)
    gg.refineNumber("0.00005120005",16,false,gg.SIGN_EQUAL,0,-1)
    gg.getResults(10000)
    gg.editAll("0.00100000005",16)
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_APP)
    gg.searchNumber("1.51061000005", 16,false,gg.SIGN_EQUAL,0, -1)
    gg.refineNumber("1.51061000005",16,false,gg.SIGN_EQUAL,0,-1)
    gg.getResults(1000)
    gg.editAll("0.00100000005",16)
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_APP)
    gg.searchNumber("0.00100000005", 16,false,gg.SIGN_EQUAL,0, -1)
    gg.refineNumber("0.00100000005",16,false,gg.SIGN_EQUAL,0,-1)
    gg.getResults(1000)
    gg.editAll("0.00061000005",16)
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_SYS)
    gg.searchNumber("0.00005120005", 16,false,gg.SIGN_EQUAL,0, -1)
    gg.refineNumber("0.00005120005",16,false,gg.SIGN_EQUAL,0,-1)
    gg.getResults(10000)
    gg.editAll("0.00100000005",16)
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_SYS)
    gg.searchNumber("1.51061000005", 16,false,gg.SIGN_EQUAL,0, -1)
    gg.refineNumber("1.51061000005",16,false,gg.SIGN_EQUAL,0,-1)
    gg.getResults(1000)
    gg.editAll("0.00100000005",16)
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_SYS)
    gg.searchNumber("0.00100000005", 16,false,gg.SIGN_EQUAL,0, -1)
    gg.refineNumber("0.00100000005",16,false,gg.SIGN_EQUAL,0,-1)
    gg.getResults(1000)
    gg.editAll("0.00061000005",16)
end
end
function D4()
  F = gg["alert"]("Recarregar Rapida ", "V1", "V2")
  if F == 1 then
    gg["clearResults"]()
    gg["setRanges"](32)
    gg["searchNumber"]("2.10000014305", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg["refineNumber"]("2.10000014305", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg["getResults"](10000)
    gg["editAll"]("1.3", 16)
    gg["toast"]("50%")
    gg["clearResults"]()
    gg["setRanges"](32)
    gg["searchNumber"]("1.23314265e-42;1.9~5.5;7.93134931e-43", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg["refineNumber"]("1.9~5.5", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg["getResults"](10000)
    gg["editAll"]("0.0000001", 16)
    gg["toast"]("■■■■■ 100% Recarregar Rapida")
  elseif F == 2 then
    gg["clearResults"]()
    gg["setRanges"](32)
    gg["searchNumber"]("0.8999999761581421;0.20000000298023224;0.375", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg["searchNumber"]("0.20000000298023224", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg["getResults"](999)
    gg["editAll"]("0.00001", gg.TYPE_FLOAT)
    gg["toast"]("Loading…")
    gg["clearResults"]()
    gg["setRanges"](32)
    gg["searchNumber"]("864D;2.16666674614F", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg["searchNumber"]("2.16666674614", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg["getResults"](999)
    gg["editAll"]("0.00001", gg.TYPE_FLOAT)
    gg["toast"]("10%")
    gg["setRanges"](32)
    gg["searchNumber"]("2.66666674614;864D", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg["searchNumber"]("2.66666674614", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg["getResults"](999)
    gg["editAll"]("0.00001", gg.TYPE_FLOAT)
    gg["toast"]("20%")
    gg["clearResults"]()
    gg["setRanges"](32)
    gg["searchNumber"]("2.90000009537", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg["searchNumber"]("2.90000009537", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg["getResults"](999)
    gg["editAll"]("0.00001", gg.TYPE_FLOAT)
    gg["toast"]("50%")
    gg["clearResults"]()
    gg["setRanges"](32)
    gg["searchNumber"]("2.03333353996", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg["searchNumber"]("2.03333353996", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg["getResults"](999)
    gg["editAll"]("0.00001", gg.TYPE_FLOAT)
    gg["toast"]("60%")
    gg["clearResults"]()
    gg["setRanges"](32)
    gg["searchNumber"]("864D;2.16666674614F", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg["searchNumber"]("2.16666674614F", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg["getResults"](999)
    gg["editAll"]("0.00001", gg.TYPE_FLOAT)
    gg["toast"]("90%")
    gg["setRanges"](32)
    gg["searchNumber"]("2.66666674614;864D", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg["searchNumber"]("2.66666674614", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg["getResults"](999)
    gg["editAll"]("0.00001", gg.TYPE_FLOAT)
    gg["toast"]("■■■■■ 100% Recarregar Rapida")
  end
end
function D5()
qmnb = {
    {
      ["memory"] = 16384
    },
    {
      ["name"] = "Aim Lock"
    },
    {
      ["value"] = -5.475527268489559E27,
      ["type"] = 16
    },
    {
      ["lv"] = -8.345310621825903E22,
      ["offset"] = -4,
      ["type"] = 16
    }
  }
  qmxg = {
    {
      ["value"] = 0,
      ["offset"] = 0,
      ["type"] = 16
    }
  }
  xqmnb(qmnb)
  qmnb = {
    {
      ["memory"] = 16384
    },
    {
      ["name"] = "Aim Lock"
    },
    {
      ["value"] = -1.0061304023208683E28,
      ["type"] = 16
    },
    {
      ["lv"] = -2.739546799828711E28,
      ["offset"] = -16,
      ["type"] = 16
    },
    {
      ["lv"] = -2.8333594434308064E28,
      ["offset"] = -8,
      ["type"] = 16
    },
    {
      ["lv"] = -8.360064414205169E22,
      ["offset"] = 12,
      ["type"] = 16
    },
    {
      ["lv"] = -3.601448401639823E21,
      ["offset"] = 20,
      ["type"] = 16
    }
  }
  qmxg = {
    {
      ["value"] = 0,
      ["offset"] = 0,
      ["type"] = 16
    }
  }
  xqmnb(qmnb)
  qmnb = {
    {
      ["memory"] = 16384
    },
    {
      ["name"] = "Aim Lock"
    },
    {
      ["value"] = 2.200000047683716,
      ["type"] = 16
    },
    {
      ["lv"] = 0.7999999523162842,
      ["offset"] = -4,
      ["type"] = 16
    }
  }
  qmxg = {
    {
      ["value"] = 10,
      ["offset"] = 0,
      ["type"] = 16
    }
  }
  xqmnb(qmnb)
    end
function D6()
qmnb = {{memory = 32},{name = ""},{value = "12.0",type = 16},{lv = "6.0",offset = 12,type = 16},{lv = "35.0",offset = 28,type = 16},{lv = "790.0",offset = 148,type = 16},{lv = "4.0",offset = 164,type = 16},{lv = "4.0",offset = 172,type = 16},{lv = "8.0",offset = 192,type = 16}}qmxg = {{value = 0,offset = 0,type = 16},{value = 0,offset = 12,type = 16},{value = 0,offset = 28,type = 16},{value = 99999,offset = 148,type = 16},{value = 0,offset = 164,type = 16},{value = 0,offset = 172,type = 16},{value = 0,offset = 192,type = 16}}xqmnb(qmnb)
qmnb = {{memory = 32},{name = ""},{value = 12, type = 16},{lv = "6.0",offset = 12,type = 16},{lv = "35.0",offset = 28,type = 16},{lv = "830.0",offset = 148,type = 16},{lv = "4.0",offset = 164,type = 16},{lv = "4.0",offset = 172,type = 16},{lv = "8.0",offset = 192,type = 16}}qmxg = {{value = 0,offset = 0,type = 16},{value = 0,offset = 12,type = 16},{value = 0,offset = 28,type = 16},{value = 99999,offset = 148,type = 16},{value = 0,offset = 164,type = 16},{value = 0,offset = 172,type = 16},{value = 0,offset = 192,type = 16}}xqmnb(qmnb)
qmnb = {{memory = 32},{name = ""},{value = 14, type = 16},{lv = "6.0",offset = 12,type = 16},{lv = "40.0",offset = 28,type = 16},{lv = "735.0",offset = 148,type = 16},{lv = "4.0",offset = 164,type = 16},{lv = "4.0",offset = 172,type = 16},{lv = "8.0",offset = 192,type = 16}}qmxg = {{value = 0,offset = 0,type = 16},{value = 0,offset = 12,type = 16},{value = 0,offset = 28,type = 16},{value = 99999,offset = 148,type = 16},{value = 0,offset = 164,type = 16},{value = 0,offset = 172,type = 16},{value = 0,offset = 192,type = 16}}xqmnb(qmnb)
qmnb = {{memory = 32},{name = ""},{value = 45, type = 16},{lv = "3.0",offset = 12,type = 16},{lv = "60.0",offset = 28,type = 16},{lv = "300.0",offset = 148,type = 16},{lv = "15.0",offset = 164,type = 16},{lv = "8.0",offset = 192,type = 16}}qmxg = {{value = 0,offset = 0,type = 16},{value = 0,offset = 12,type = 16},{value = 0,offset = 28,type = 16},{value = 99999,offset = 148,type = 16},{value = 0,offset = 164,type = 16},{value = 0,offset = 192,type = 16}}xqmnb(qmnb)
qmnb = {{memory = 32},{name = ""},{value = 15, type = 16},{lv = "3.0",offset = 12,type = 16},{lv = "25.0",offset = 28,type = 16},{lv = "300.0",offset = 148,type = 16},{lv = "4.0",offset = 164,type = 16},{lv = "4.0",offset = 172,type = 16},{lv = "1.0",offset = 192,type = 16}}qmxg = {{value = 0,offset = 0,type = 16},{value = 0,offset = 12,type = 16},{value = 0,offset = 28,type = 16},{value = 99999,offset = 148,type = 16},{value = 0,offset = 164,type = 16},{value = 0,offset = 172,type = 16},{value = 0,offset = 192,type = 16}}xqmnb(qmnb)
qmnb = {{memory = 32},{name = ""},{value = "735.0",type = 16},{lv = "15.0",offset = -148,type = 16},{lv = "33.0",offset = -144,type = 16},{lv = "6.0",offset = -136,type = 16},{lv = "20.0",offset = -108,type = 16},{lv = "10.0",offset = -96,type = 16},{lv = "10.0",offset = -92,type = 16},{lv = "10.0",offset = -88,type = 16},{lv = "4.0",offset = 16,type = 16},{lv = "4.0",offset = 24,type = 16},{lv = "1.0",offset = 160,type = 16}}qmxg = {{value = 0,offset = -148,type = 16},{value = 0,offset = -144,type = 16},{value = 0,offset = -136,type = 16},{value = 0,offset = -108,type = 16},{value = 0,offset = -96,type = 16},{value = 0,offset = -92,type = 16},{value = 0,offset = -88,type = 16},{value = 9999,offset = 0,type = 16},{value = 0,offset = 16,type = 16},{value = 0,offset = 24,type = 16},{value = 0,offset = 160,type = 16}}xqmnb(qmnb)
qmnb = {{memory = 32},{name = ""},{value = 16, type = 16},{lv = "2.0",offset = 12,type = 16},{lv = "30.0",offset = 28,type = 16},{lv = "320.0",offset = 148,type = 16},{lv = "4.0",offset = 164,type = 16},{lv = "4.0",offset = 172,type = 16},{lv = "5.0",offset = 192,type = 16}}qmxg = {{value = 0,offset = 0,type = 16},{value = 0,offset = 12,type = 16},{value = 0,offset = 28,type = 16},{value = 99999,offset = 148,type = 16},{value = 0,offset = 164,type = 16},{value = 0,offset = 172,type = 16},{value = 0,offset = 192,type = 16}}xqmnb(qmnb)
qmnb = {{memory = 32},{name = ""},{value = 15, type = 16},{lv = "6.0",offset = 12,type = 16},{lv = "30.0",offset = 28,type = 16},{lv = "710.0",offset = 148,type = 16},{lv = "4.0",offset = 164,type = 16},{lv = "4.0",offset = 172,type = 16},{lv = "8.0",offset = 192,type = 16}}qmxg = {{value = 0,offset = 0,type = 16},{value = 0,offset = 12,type = 16},{value = 0,offset = 28,type = 16},{value = 99999,offset = 148,type = 16},{value = 0,offset = 164,type = 16},{value = 0,offset = 172,type = 16},{value = 0,offset = 192,type = 16}}xqmnb(qmnb)
qmnb = {{memory = 32},{name = ""},{value = 15, type = 16},{lv = "3.0",offset = 12,type = 16},{lv = "10.0",offset = 40,type = 16},{lv = "4.0",offset = 112,type = 16},{lv = "4.0",offset = 116,type = 16},{lv = "2.799999952316284",offset = 120,type = 16},{lv = "40.0",offset = 148,type = 16}}qmxg = {{value = 0,offset = 0,type = 16},{value = 0,offset = 12,type = 16},{value = 0,offset = 40,type = 16},{value = 0,offset = 112,type = 16},{value = 0,offset = 116,type = 16},{value = 9999,offset = 148,type = 16}}xqmnb(qmnb)
qmnb = {{memory = 32},{name = ""},{value = 24, type = 16},{lv = "24.0",offset = 12,type = 16},{lv = "10.0",offset = 40,type = 16},{lv = "4.0",offset = 112,type = 16},{lv = "4.0",offset = 116,type = 16},{lv = "2.799999952316284",offset = 120,type = 16},{lv = "25.0",offset = 148,type = 16}}qmxg = {{value = 0,offset = 0,type = 16},{value = 0,offset = 12,type = 16},{value = 0,offset = 40,type = 16},{value = 0,offset = 112,type = 16},{value = 0,offset = 116,type = 16},{value = 9999,offset = 148,type = 16}}xqmnb(qmnb)
qmnb = {{memory = 32},{name = ""},{value = "480.0",type = 16},{lv = "20.0",offset = -148,type = 16},{lv = "40.0",offset = -144,type = 16},{lv = "6.0",offset = -136,type = 16},{lv = "60.0",offset = -120,type = 16},{lv = "0.5",offset = -100,type = 16},{lv = "4.0",offset = 16,type = 16},{lv = "4.0",offset = 24,type = 16},{lv = "1.0",offset = 160,type = 16}}qmxg = {{value = 0,offset = -148,type = 16},{value = 0,offset = -144,type = 16},{value = 0,offset = -136,type = 16},{value = 0,offset = -120,type = 16},{value = 0,offset = -100,type = 16},{value = 9999,offset = 0,type = 16},{value = 0,offset = 16,type = 16},{value = 0,offset = 24,type = 16},{value = 0,offset = 160,type = 16}}xqmnb(qmnb)
qmnb = {{memory = 32},{name = ""},{value = 45, type = 16},{lv = "3.0",offset = 12,type = 16},{lv = "60.0",offset = 28,type = 16},{lv = "300.0",offset = 148,type = 16},{lv = "13.0",offset = 164,type = 16},{lv = "8.0",offset = 192,type = 16}}qmxg = {{value = 0,offset = 0,type = 16},{value = 0,offset = 12,type = 16},{value = 0,offset = 28,type = 16},{value = 99999,offset = 148,type = 16},{value = 0,offset = 164,type = 16},{value = 0,offset = 192,type = 16}}xqmnb(qmnb)
qmnb = {{memory = 32},{name = ""},{value = 14, type = 16},{lv = "3.0",offset = 12,type = 16},{lv = "25.0",offset = 28,type = 16},{lv = "360.0",offset = 148,type = 16},{lv = "4.0",offset = 164,type = 16},{lv = "4.0",offset = 172,type = 16},{lv = "5.0",offset = 192,type = 16}}qmxg = {{value = 0,offset = 0,type = 16},{value = 0,offset = 12,type = 16},{value = 0,offset = 28,type = 16},{value = 99999,offset = 148,type = 16},{value = 0,offset = 164,type = 16},{value = 0,offset = 172,type = 16},{value = 0,offset = 192,type = 16}}xqmnb(qmnb)
qmnb = {{memory = 32},{name = ""},{value = 45, type = 16},{lv = "3.0",offset = 12,type = 16},{lv = "60.0",offset = 28,type = 16},{lv = "300.0",offset = 148,type = 16},{lv = "15.0",offset = 164,type = 16},{lv = "8.0",offset = 192,type = 16}}qmxg = {{value = 0,offset = 0,type = 16},{value = 0,offset = 12,type = 16},{value = 0,offset = 28,type = 16},{value = 99999,offset = 148,type = 16},{value = 0,offset = 164,type = 16},{value = 0,offset = 192,type = 16}}xqmnb(qmnb)
end
function D7()
  kk = gg.prompt({
 "high view (sitting) [-100;100]",}, {data}, {"number"})
 gg.clearResults()
  gg.setRanges(32)
  gg.searchNumber("1.5;-40;80;-360;360;56;131072E;8;::90", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.searchNumber("1.5", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
  gg.getResults(100)
  gg.editAll(kk[1], gg.TYPE_FLOAT)
  gg.clearResults(100)
end

function H1()
SN7 = gg.choice({
"☠️┣ Bala Mágica 50% ●",
"☠️┣ Bala Mágica 70% ●",
"☠️┣ Bala Mágica 100% ●",
"Voltar",
}, nil,"┣【 Zark Mod 】┫")
if SN7 == 1 then 
IO()
end
if SN7 == 2 then 
OI()
end
if SN7 == 3then 
IK()
end
if SN7 == 3 then
HOME()
end
XGCK = -1
end
function IO()
  gg["clearResults"](32)
  SearchWrite({
    {1060152279,0,4},
    {1042536202,-4,4}, 
    {1092616192,0,4}
    }, {
     {0, 4}
    }, 4)
  gg["clearResults"](32)
  SearchWrite({
    {1056293519,0,4},
    {1035489772,-4,4}, 
    {1092616192,0,4}
    }, {
     {0, 4,}
    }, 4)

gg["clearResults"](32)
  SearchWrite({
    {1050253722,0,4},
    {1031127695,-4,4}, 
    {1092616192,0,4}
    }, {
     {0, 4}
    }, 4)
  gg["clearResults"](32)
  SearchWrite({
    {1055286886,0,4},
    {1025758986,-4,4}, 
    {1092616192,0,4}
    }, {
     {0, 4}
    }, 4)
  gg["clearResults"](32)
  SearchWrite({
    {1051595899,0,4},
    {1038174126,-4,4}, 
    {1092616192,0,4}
    }, {
     {0, 0,4}
    }, 4)
  gg["clearResults"](32)
  SearchWrite({
    {1057635697,0,4},
    {1035489772,-4,4}, 
    {1092616192,0,4}
    }, {
     {0, 4}
    }, 4)
  gg["clearList"]()
end
function OI()
qmnb = {
  {memory = 32},
  {
    name = "■□□□□ 20%"
  },
  {value = 0.5400000214576721, type = 16},
  {
    lv = 0.09000000357627869,
    offset = -4,
    type = 16
  }
}
qmxg = {
  {
    value = 8,
    offset = 0,
    type = 16
  }
}
xqmnb(qmnb)

qmnb = {
  {memory = 32},
  {
    name = "■■□□□ 40%"
  },
  {value = 0.6899999976158142, type = 16},
  {
    lv = 0.1599999964237213,
    offset = -4,
    type = 16
  }
}
qmxg = {
  {
    value = 8,
    offset = 0,
    type = 16
  }
}
xqmnb(qmnb)
qmnb = {
  {memory = 32},
  {
    name = "■■■□□ 60%"
  },
  {value = 0.47999998927116394, type = 16},
  {
    lv = 0.09000000357627869,
    offset = -4,
    type = 16
  }
}
qmxg = {
  {
    value = 8,
    offset = 0,
    type = 16
  }
}
xqmnb(qmnb)  

qmnb = {
  {memory = 32},
  {
    name = "■■■■□ 80%"
  },
  {value = 0.44999998807907104, type = 16},
  {
    lv = 0.03999999910593033,
    offset = -4,
    type = 16
  }
}
qmxg = {
  {
    value = 8,
    offset = 0,
    type = 16
  }
}
xqmnb(qmnb)
qmnb = {
  {memory = 32},
  {name = "■■■■■ 100%"},
  {value = 0.3400000035762787, type = 16},
  {
    lv = 0.10999999940395355,
    offset = -4,
    type = 16
  }
}
qmxg = {
  {
    value = 8,
    offset = 0,
    type = 16
  }
}
xqmnb(qmnb)
end
function OI()
qmnb = {
  {memory = 32},
  {
    name = "■□□□□ 20%"
  },
  {value = 0.5400000214576721, type = 16},
  {
    lv = 0.09000000357627869,
    offset = -4,
    type = 16
  }
}
qmxg = {
  {
    value = 1,
    offset = 0,
    type = 16
  }
}
xqmnb(qmnb)

qmnb = {
  {memory = 32},
  {
    name = "■■□□□ 40%"
  },
  {value = 0.6899999976158142, type = 16},
  {
    lv = 0.1599999964237213,
    offset = -4,
    type = 16
  }
}
qmxg = {
  {
    value = 1,
    offset = 0,
    type = 16
  }
}
xqmnb(qmnb)
qmnb = {
  {memory = 32},
  {
    name = "■■■□□ 60%"
  },
  {value = 0.47999998927116394, type = 16},
  {
    lv = 0.09000000357627869,
    offset = -4,
    type = 16
  }
}
qmxg = {
  {
    value = 1,
    offset = 0,
    type = 16
  }
}
xqmnb(qmnb)  

qmnb = {
  {memory = 32},
  {
    name = "■■■■□ 80%"
  },
  {value = 0.44999998807907104, type = 16},
  {
    lv = 0.03999999910593033,
    offset = -4,
    type = 16
  }
}
qmxg = {
  {
    value = 1,
    offset = 0,
    type = 16
  }
}
xqmnb(qmnb)
qmnb = {
  {memory = 32},
  {name = "■■■■■ 100%"},
  {value = 0.3400000035762787, type = 16},
  {
    lv = 0.10999999940395355,
    offset = -4,
    type = 16
  }
}
qmxg = {
  {
    value = 1,
    offset = 0,
    type = 16
  }
}
xqmnb(qmnb)
end
function IK()
qmnb = {
    {memory = 32},
    {name = "□□□□□ 0%"},
    {value = 0.6899999976158142, type = 16},
    {
      lv = 0.1599999964237213,
      offset = -4,
      type = 16
    }
  }
  qmxg = {
    {
      value = 99,
      offset = 0,
      type = 16
    }
  }
  xqmnb(qmnb)
  qmnb = {
    {memory = 32},
    {name = "■□□□□ 20%"},
    {value = 0.47999998927116394, type = 16},
    {
      lv = 0.09000000357627869,
      offset = -4,
      type = 16
    }
  }
  qmxg = {
    {
      value = 99,
      offset = 0,
      type = 16
    }
  }
  xqmnb(qmnb)
  qmnb = {
    {memory = 32},
    {name = "■■□□□ 40%"},
    {value = 0.30000001192092896, type = 16},
    {
      lv = 0.05999999865889549,
      offset = -4,
      type = 16
    }
  }
  qmxg = {
    {
      value = 99,
      offset = 0,
      type = 16
    }
  }
  xqmnb(qmnb)
  qmnb = {
    {memory = 32},
    {name = "■■■□□ 60%"},
    {value = 0.44999998807907104, type = 16},
    {
      lv = 0.03999999910593033,
      offset = -4,
      type = 16
    }
  }
  qmxg = {
    {
      value = 99,
      offset = 0,
      type = 16
    }
  }
  xqmnb(qmnb)
  qmnb = {
    {memory = 32},
    {name = "■■■□□ 70%"},
    {value = 0.3400000035762787, type = 16},
    {
      lv = 0.10999999940395355,
      offset = -4,
      type = 16
    }
  }
  qmxg = {
    {
      value = 99,
      offset = 0,
      type = 16
    }
  }
  xqmnb(qmnb)
  qmnb = {
    {memory = 32},
    {name = "■■■■□ 80%"},
    {value = 0.5400000214576721, type = 16},
    {
      lv = 0.09000000357627869,
      offset = -4,
      type = 16
    }
  }
  qmxg = {
    {
      value = 99,
      offset = 0,
      type = 16
    }
  }
  xqmnb(qmnb)
  qmnb = {
    {memory = 32},
    {name = "■■■■■ 100%"},
    {value = 0.30000001192092896, type = 16},
    {
      lv = 0.05999999865889549,
      offset = -4,
      type = 16
    }
  }
  qmxg = {
    {
      value = 99,
      offset = 0,
      type = 16
    }
  }
  xqmnb(qmnb)
  gg["setRanges"](gg["REGION_ANONYMOUS"])
  gg["searchNumber"]("0.47999998927116394", gg["TYPE_FLOAT"], false, gg["SIGN_EQUAL"], 0, -1)
  gg["getResults"](999)
  gg["editAll"]("99", gg["TYPE_FLOAT"])
  gg["toast"]("80%")
  gg["setRanges"](gg["REGION_ANONYMOUS"])
  gg["refineNumber"]("0.3400000035762787")
  gg["getResults"](999)
  gg["editAll"]("99", gg["TYPE_FLOAT"])
  gg["toast"]("90%")
  gg["setRanges"](gg["REGION_ANONYMOUS"])
  gg["searchNumber"]("0.6899999976158142", gg["TYPE_FLOAT"], false, gg["SIGN_EQUAL"], 0, -1)
  gg["getResults"](999)
  gg["editAll"]("99", gg["TYPE_FLOAT"])
  gg["toast"]("100%")
end
function H2()
F = gg.alert("Anti-Bot ", "ON", "OFF")
    if F == 1 then
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_APP)
    gg.searchNumber("0.00061000005", 16,false,gg.SIGN_EQUAL,0, -1)
    gg.refineNumber("0.00061000005",16,false,gg.SIGN_EQUAL,0,-1)
    gg.getResults(10000)
    gg.editAll("0.00100000005",16)
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_APP)
    gg.searchNumber("0.00005120005", 16,false,gg.SIGN_EQUAL,0, -1)
    gg.refineNumber("0.00005120005",16,false,gg.SIGN_EQUAL,0,-1)
    gg.getResults(10000)
    gg.editAll("0.00100000005",16)
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_SYS)
    gg.searchNumber("0.00061000005", 16,false,gg.SIGN_EQUAL,0, -1)
    gg.refineNumber("0.00061000005",16,false,gg.SIGN_EQUAL,0,-1)
    gg.getResults(10000)
    gg.editAll("0.00100000005",16)
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_SYS)
    gg.searchNumber("0.00005120005", 16,false,gg.SIGN_EQUAL,0, -1)
    gg.refineNumber("0.00005120005",16,false,gg.SIGN_EQUAL,0,-1)
    gg.getResults(10000)
    gg.editAll("0.00100000005",16)
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_APP)
    gg.searchNumber("0.00100000005", 16,false,gg.SIGN_EQUAL,0, -1)
    gg.refineNumber("0.00100000005",16,false,gg.SIGN_EQUAL,0,-1)
    gg.getResults(1000)
    gg.editAll("1.51061000005",16)
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_SYS)
    gg.searchNumber("0.00100000005", 16,false,gg.SIGN_EQUAL,0, -1)
    gg.refineNumber("0.00100000005",16,false,gg.SIGN_EQUAL,0,-1)
    gg.getResults(1000)
    gg.editAll("1.51061000005",16)
    elseif F == 2 then
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_APP)
    gg.searchNumber("1.51061000005", 16,false,gg.SIGN_EQUAL,0, -1)
    gg.refineNumber("1.51061000005",16,false,gg.SIGN_EQUAL,0,-1)
    gg.getResults(1000)
    gg.editAll("0.00100000005",16)
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_SYS)
    gg.searchNumber("1.51061000005", 16,false,gg.SIGN_EQUAL,0, -1)
    gg.refineNumber("1.51061000005",16,false,gg.SIGN_EQUAL,0,-1)
    gg.getResults(1000)
    gg.editAll("0.00100000005",16)
    end
    end
function H3()
F = gg["alert"]("Penetra paredes ou pedras. Edifícios não podem ser penetrados", "ligar", "Fechar")
  if F == 1 then
    qmnb = {
      {
        ["memory"] = 32
      },
      {
        ["name"] = "■■□□□ 40%"
      },
      {
        ["value"] = 6.699999809265137,
        ["type"] = 16
      },
      {
        ["lv"] = 0.10000000149011612,
        ["offset"] = 16,
        ["type"] = 16
      },
      {
        ["lv"] = 0.009999999776482582,
        ["offset"] = 20,
        ["type"] = 16
      },
      {
        ["lv"] = 0.10000000149011612,
        ["offset"] = 24,
        ["type"] = 16
      }
    }
    qmxg = {
      {
        ["value"] = -9,
        ["offset"] = 16,
        ["type"] = 16
      },
      {
        ["value"] = -9,
        ["offset"] = 24,
        ["type"] = 16
      }
    }
    xqmnb(qmnb)
    qmnb = {
      {
        ["memory"] = 32
      },
      {
        ["name"] = "■■■■□ 80%"
      },
      {
        ["value"] = 999,
        ["type"] = 16
      },
      {
        ["lv"] = 0.10000000149011612,
        ["offset"] = 16,
        ["type"] = 16
      },
      {
        ["lv"] = 0.004999999888241291,
        ["offset"] = 24,
        ["type"] = 16
      }
    }
    qmxg = {
      {
        ["value"] = 8.88479995728,
        ["offset"] = 20,
        ["type"] = 16
      }
    }
    xqmnb(qmnb)
  elseif F == 2 then
    qmnb = {
      {
        ["memory"] = 32
      },
      {
        ["name"] = "■■■■■ 100%"
      },
      {
        ["value"] = 999,
        ["type"] = 16
      },
      {
        ["lv"] = 0.10000000149011612,
        ["offset"] = 16,
        ["type"] = 16
      },
      {
        ["lv"] = 0.004999999888241291,
        ["offset"] = 24,
        ["type"] = 16
      }
    }
    qmxg = {
      {
        ["value"] = 1.00000003E32,
        ["offset"] = 20,
        ["type"] = 16
      }
    }
    xqmnb(qmnb)
  end
end
function H4()
      F = gg.alert("Velocidade", "Executar","Desligado","Rápido Farm")
  if F == 1 then
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_APP)
    gg.searchNumber("0.14777720249", 16,false,gg.SIGN_EQUAL,0, -1)
    gg.getResults(300)
    gg.editAll("0.14177720249",16)
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_APP)
    gg.searchNumber("4.90000019073", 16,false,gg.SIGN_EQUAL,0, -1)
    gg.getResults(1000)
    gg.editAll("6.30000019073",16)
    gg.clearResults()
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_APP)
    gg.searchNumber("0.14177720249", 16,false,gg.SIGN_EQUAL,0, -1)
    gg.getResults(300)
    gg.editAll("0.15777720249",16)
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_APP)
    gg.searchNumber("6.30000019073", 16,false,gg.SIGN_EQUAL,0, -1)
    gg.getResults(1000)
    gg.editAll("3.100012345",16)
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_SYS)
    gg.searchNumber("0.14777720249", 16,false,gg.SIGN_EQUAL,0, -1)
    gg.getResults(300)
    gg.editAll("0.14177720249",16)
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_SYS)
    gg.searchNumber("4.90000019073", 16,false,gg.SIGN_EQUAL,0, -1)
    gg.getResults(1000)
    gg.editAll("6.30000019073",16)
    gg.clearResults()
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_SYS)
    gg.searchNumber("0.14177720249", 16,false,gg.SIGN_EQUAL,0, -1)
    gg.getResults(300)
    gg.editAll("0.15777720249",16)
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_SYS)
    gg.searchNumber("6.30000019073", 16,false,gg.SIGN_EQUAL,0, -1)
    gg.getResults(1000)
    gg.editAll("3.100012345",16)
    elseif F == 2 then
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_APP)
    gg.searchNumber("0.14777720249", 16,false,gg.SIGN_EQUAL,0, -1)
    gg.getResults(300)
    gg.editAll("0.14177720249",16)
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_APP)
    gg.searchNumber("4.90000019073", 16,false,gg.SIGN_EQUAL,0, -1)
    gg.getResults(1000)
    gg.editAll("6.30000019073",16)
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_APP)
    gg.searchNumber("0.15777720249", 16,false,gg.SIGN_EQUAL,0, -1)
    gg.getResults(300)
    gg.editAll("0.14177720249",16)
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_APP)
    gg.searchNumber("3.100012345", 16,false,gg.SIGN_EQUAL,0, -1)
    gg.getResults(1000)
    gg.editAll("6.30000019073",16)
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_SYS)
    gg.searchNumber("0.14777720249", 16,false,gg.SIGN_EQUAL,0, -1)
    gg.getResults(300)
    gg.editAll("0.14177720249",16)
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_SYS)
    gg.searchNumber("4.90000019073", 16,false,gg.SIGN_EQUAL,0, -1)
    gg.getResults(1000)
    gg.editAll("6.30000019073",16)
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_SYS)
    gg.searchNumber("0.15777720249", 16,false,gg.SIGN_EQUAL,0, -1)
    gg.getResults(300)
    gg.editAll("0.14177720249",16)
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_SYS)
    gg.searchNumber("3.100012345", 16,false,gg.SIGN_EQUAL,0, -1)
    gg.getResults(1000)
    gg.editAll("6.30000019073",16)
    elseif F == 3 then
    gg.setRanges(gg.REGION_CODE_APP)
    gg.searchNumber("0.15777720249", 16,false,gg.SIGN_EQUAL,0, -1)
    gg.getResults(300)
    gg.editAll("0.14177720249",16)
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_APP)
    gg.searchNumber("3.100012345", 16,false,gg.SIGN_EQUAL,0, -1)
    gg.getResults(1000)
    gg.editAll("6.30000019073",16)
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_APP)
    gg.searchNumber("0.14177720249", 16,false,gg.SIGN_EQUAL,0, -1)
    gg.getResults(300)
    gg.editAll("0.14777720249",16)
    gg.clearList() 
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_APP)
    gg.searchNumber("6.30000019073", 16,false,gg.SIGN_EQUAL,0, -1)
    gg.getResults(1000)
    gg.editAll("4.90000019073",16)
    gg.setRanges(gg.REGION_CODE_SYS)
    gg.searchNumber("0.15777720249", 16,false,gg.SIGN_EQUAL,0, -1)
    gg.getResults(300)
    gg.editAll("0.14177720249",16)
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_SYS)
    gg.searchNumber("3.100012345", 16,false,gg.SIGN_EQUAL,0, -1)
    gg.getResults(1000)
    gg.editAll("6.30000019073",16)
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_SYS)
    gg.searchNumber("0.14177720249", 16,false,gg.SIGN_EQUAL,0, -1)
    gg.getResults(300)
    gg.editAll("0.14777720249",16)
    gg.clearList() 
    gg.clearResults()
    gg.setRanges(gg.REGION_CODE_SYS)
    gg.searchNumber("6.30000019073", 16,false,gg.SIGN_EQUAL,0, -1)
    gg.getResults(1000)
    gg.editAll("4.90000019073",16)
    qmnb = {
{["memory"] = 32},
{["name"] = "Open"},
{["value"] = 1.233142648605839E-42, ["type"] = 16},
{["lv"] = 4.0, ["offset"] = 12, ["type"] = 16},
{["lv"] = 7.987401246651457E-43, ["offset"] = 60, ["type"] = 16},
}
qmxg = {
{["value"] = 6.7, ["offset"] = 12, ["type"] = 16},

}
xqmnb(qmnb)
qmnb = {
{["memory"] = 32},
{["name"] = "Open"},
{["value"] = 1.233142648605839E-42, ["type"] = 16},
{["lv"] = 8.0, ["offset"] = 12, ["type"] = 16},
{["lv"] = 7.847271400218976E-43, ["offset"] = 60, ["type"] = 16},
}
qmxg = {
{["value"] = 9.3, ["offset"] = 12, ["type"] = 16},
}
xqmnb(qmnb)
end
end
function H5()
vp = gg.prompt({
"🏃 sprint 🏃 [0;20] "
}, {1.5}, {"number"})
if vp == nil then
do return end
return
end
if loadcodd == false then
gg.clearResults()
gg.setRanges(32768)
gg.searchNumber("6.30000019073", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.searchNumber("6.30000019073", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
gg.addListItems((gg.getResults(1)))
gg.saveList(gg.EXT_STORAGE .. "/./fuck.txt", 0)
gg.clearResults()
gg.clearList()
loadcodd = true
end
gg.loadList(gg.EXT_STORAGE .. "/./fuck.txt", 0)
a = gg.getListItems()
gg.loadResults(a)
gg.removeListItems(a)
g = gg.getResults(1)
gg.editAll(vp[1], 16)
end
function G2()
  F = gg.alert("Andar debaixo d'água", "Ligado", "Desligado")
  if F == 1 then
    gg.clearResults()
    gg.setRanges(32)
    gg.searchNumber("1.0F;0.00999999978F;3.7835059e-43F;4.2038954e-45F;10,000.0F;10,000.001953125F", gg.REGION_C_BSS, false, gg.SIGN_FUZZY_EQUAL, 0, -1)
    gg.searchNumber("10000", gg.REGION_C_BSS, false, gg.SIGN_FUZZY_EQUAL, 0, -1)
    gg.getResults(999)
    gg.editAll("0.0012345", gg.REGION_C_BSS)
    gg.clearResults()
  elseif F == 2 then
    gg.clearResults()
    gg.setRanges(32)
    gg.searchNumber("0.0012345", gg.TYPE_FLOAT, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(999)
    gg.editAll("10000", gg.TYPE_FLOAT)
    gg.clearResults()
  end
end
function G4()
gg["setRanges"](gg['REGION_CODE_SYS'])
gg["searchNumber"]("1.19622647762", gg["TYPE_FLOAT"], false, gg["SIGN_EQUAL"], 0, -1)
gg["getResults"](1)
gg["editAll"]("100", gg["TYPE_FLOAT"])
gg["toast"]("เปิด")
end
function G5()
  F = gg.alert("Construção Subterrânea", "V2", "Desligado", "V1")
  if F == 1 then
    qmnb = {
      {memory = 32},
      {name = "Open"},
      {value = 2.755148962647596E-40, type = 16},
      {
        lv = 2.3509885615147286E-38,
        offset = -48,
        type = 16
      },
      {
        lv = -0.7071068286895752,
        offset = -40,
        type = 16
      },
      {
        lv = 0.7071068286895752,
        offset = -28,
        type = 16
      },
      {
        lv = 0,
        offset = -20,
        type = 16
      }
    }
    qmxg = {
      {
        value = -2,
        offset = -20,
        type = 16
      }
    }
    xqmnb(qmnb)
  elseif F == 2 then
    gg.setRanges(32)
    gg.searchNumber("-2", 16, false, 536870912, 0, -1, 0)
    gg.getResults(9000)
    gg.editAll("0", gg.TYPE_FLOAT)
    gg.clearResults()
    gg.toast("Close")
  elseif F == 3 then
    gg.clearResults()
    gg.setRanges(32)
    gg.searchNumber("2.35098856e-38;1.40129846e-45;-0.70710682869;0.70710682869;0.0::35", 16, false, 536870912, 0, -1, 0)
    gg.refineNumber("0", 16, false, 536870912, 0, -1, 0)
    gg.getResults(9000)
    gg.editAll("-2", gg.TYPE_FLOAT)
    gg.clearResults()
    gg.toast("Open")
  end
end
function G7()
  F = gg.alert("Dia e Noite", "Ligado", "Desligado")
  if F == 1 then
    gg.clearList()
    gg.clearResults()
    gg.setRanges(32)
    gg.searchNumber("1,004,243,884D;9.2194229e-41;-1D::", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.searchNumber("9.2194229e-41", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(1)
    gg.editAll("999", 16)
    gg.clearList()
  elseif F == 2 then
    gg.clearList()
    gg.clearResults()
    gg.setRanges(32)
    gg.searchNumber("1,004,243,884D;999;-1D::", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.searchNumber("999", 16, false, gg.SIGN_EQUAL, 0, -1)
    gg.getResults(1)
    gg.editAll("9.2194229e-41", 16)
    gg.clearList()
  end
end

function X1()
gg.setRanges(gg.REGION_C_ALLOC)
gg.searchNumber("135170", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1, 0)
revert = gg.getResults(4000, nil, nil, nil, nil, nil, nil, nil, nil)
for i, i in ipairs((gg.getResults(4000, nil, nil, nil, nil, nil, nil, nil, nil))) do
if i.flags == gg.TYPE_DWORD then
i.value = "0"
i.freeze = true
end
end
gg.addListItems((gg.getResults(4000, nil, nil, nil, nil, nil, nil, nil, nil)))
gg.processResume()
gg.searchNumber("135298", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1, 0)
revert = gg.getResults(4000, nil, nil, nil, nil, nil, nil, nil, nil)
for i, i in ipairs((gg.getResults(4000, nil, nil, nil, nil, nil, nil, nil, nil))) do
if i.flags == gg.TYPE_DWORD then
i.value = "0"
i.freeze = true
end
end
gg.addListItems((gg.getResults(4000, nil, nil, nil, nil, nil, nil, nil, nil)))
gg.processResume()
gg.searchNumber("131202", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1, 0)
revert = gg.getResults(4000, nil, nil, nil, nil, nil, nil, nil, nil)
for i, i in ipairs((gg.getResults(4000, nil, nil, nil, nil, nil, nil, nil, nil))) do
if i.flags == gg.TYPE_DWORD then
i.value = "0"
i.freeze = true
end
end
gg.addListItems((gg.getResults(4000, nil, nil, nil, nil, nil, nil, nil, nil)))
gg.processResume()
gg.searchNumber("131330", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1, 0)
revert = gg.getResults(4000, nil, nil, nil, nil, nil, nil, nil, nil)
for i, i in ipairs((gg.getResults(4000, nil, nil, nil, nil, nil, nil, nil, nil))) do
if i.flags == gg.TYPE_DWORD then
i.value = "0"
i.freeze = true
end
end
gg.addListItems((gg.getResults(4000, nil, nil, nil, nil, nil, nil, nil, nil)))
gg.processResume()
gg.searchNumber("135682", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1, 0)
revert = gg.getResults(4000, nil, nil, nil, nil, nil, nil, nil, nil)
for i, i in ipairs((gg.getResults(4000, nil, nil, nil, nil, nil, nil, nil, nil))) do
if i.flags == gg.TYPE_DWORD then
i.value = "0"
i.freeze = true
end
end
gg.addListItems((gg.getResults(4000, nil, nil, nil, nil, nil, nil, nil, nil)))
gg.processResume()
gg.searchNumber("131842", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1, 0)
revert = gg.getResults(4000, nil, nil, nil, nil, nil, nil, nil, nil)
for i, i in ipairs((gg.getResults(4000, nil, nil, nil, nil, nil, nil, nil, nil))) do
if i.flags == gg.TYPE_DWORD then
i.value = "0"
i.freeze = true
end
end
gg.addListItems((gg.getResults(4000, nil, nil, nil, nil, nil, nil, nil, nil)))
gg.processResume()
gg.searchNumber("132098", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1, 0)
revert = gg.getResults(4000, nil, nil, nil, nil, nil, nil, nil, nil)
for i, i in ipairs((gg.getResults(4000, nil, nil, nil, nil, nil, nil, nil, nil))) do
if i.flags == gg.TYPE_DWORD then
i.value = "0"
i.freeze = true
end
end
gg.addListItems((gg.getResults(4000, nil, nil, nil, nil, nil, nil, nil, nil)))
gg.processResume()
gg.searchNumber("136194", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1, 0)
revert = gg.getResults(4000, nil, nil, nil, nil, nil, nil, nil, nil)
for i, i in ipairs((gg.getResults(4000, nil, nil, nil, nil, nil, nil, nil, nil))) do
if i.flags == gg.TYPE_DWORD then
i.value = "0"
i.freeze = true
end
end
gg.addListItems((gg.getResults(4000, nil, nil, nil, nil, nil, nil, nil, nil)))
end
function X2()
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC | gg.REGION_ANONYMOUS | gg.REGION_CODE_APP)
gg.searchNumber(":TssSDKGetReportData2", gg.TYPE_BYTE, false, gg.SIGN_EQUAL, 0, -1, 0)
revert = gg.getResults(100000, nil, nil, nil, nil, nil, nil, nil, nil)
gg.editAll(":", gg.TYPE_BYTE)
gg.clearResults()
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC | gg.REGION_ANONYMOUS | gg.REGION_CODE_APP)
gg.searchNumber(":TssSDKGetReportData3", gg.TYPE_BYTE, false, gg.SIGN_EQUAL, 0, -1, 0)
revert = gg.getResults(100000, nil, nil, nil, nil, nil, nil, nil, nil)
gg.editAll(":", gg.TYPE_BYTE)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC | gg.REGION_ANONYMOUS | gg.REGION_CODE_APP)
gg.searchNumber(":TssSDKGetReportData", gg.TYPE_BYTE, false, gg.SIGN_EQUAL, 0, -1, 0)
revert = gg.getResults(100000, nil, nil, nil, nil, nil, nil, nil, nil)
gg.editAll(":", gg.TYPE_BYTE)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC | gg.REGION_ANONYMOUS | gg.REGION_CODE_APP)
gg.searchNumber(":TssSDKDelReportData", gg.TYPE_BYTE, false, gg.SIGN_EQUAL, 0, -1, 0)
revert = gg.getResults(100000, nil, nil, nil, nil, nil, nil, nil, nil)
gg.editAll(":", gg.TYPE_BYTE)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC | gg.REGION_ANONYMOUS | gg.REGION_CODE_APP)
gg.searchNumber(":TssSDKDelReportData3", gg.TYPE_BYTE, false, gg.SIGN_EQUAL, 0, -1, 0)
revert = gg.getResults(100000, nil, nil, nil, nil, nil, nil, nil, nil)
gg.editAll(":", gg.TYPE_BYTE)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC | gg.REGION_ANONYMOUS | gg.REGION_CODE_APP)
gg.searchNumber(":tss_sdk_rcv_anti_data", gg.TYPE_BYTE, false, gg.SIGN_EQUAL, 0, -1, 0)
revert = gg.getResults(100000, nil, nil, nil, nil, nil, nil, nil, nil)
gg.editAll(":", gg.TYPE_BYTE)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC | gg.REGION_ANONYMOUS | gg.REGION_CODE_APP)
gg.searchNumber(":tss_sdk_setuserinfo", gg.TYPE_BYTE, false, gg.SIGN_EQUAL, 0, -1, 0)
revert = gg.getResults(100000, nil, nil, nil, nil, nil, nil, nil, nil)
gg.editAll(":", gg.TYPE_BYTE)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC | gg.REGION_ANONYMOUS | gg.REGION_CODE_APP)
gg.searchNumber(":tp2_sdk_ioctl", gg.TYPE_BYTE, false, gg.SIGN_EQUAL, 0, -1, 0)
revert = gg.getResults(100000, nil, nil, nil, nil, nil, nil, nil, nil)
gg.editAll(":", gg.TYPE_BYTE)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC | gg.REGION_ANONYMOUS | gg.REGION_CODE_APP)
gg.searchNumber(":tss_sdk_init", gg.TYPE_BYTE, false, gg.SIGN_EQUAL, 0, -1, 0)
revert = gg.getResults(100000, nil, nil, nil, nil, nil, nil, nil, nil)
gg.editAll(":", gg.TYPE_BYTE)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC | gg.REGION_ANONYMOUS | gg.REGION_CODE_APP)
gg.searchNumber(":tss_sdk_dec_tss_info", gg.TYPE_BYTE, false, gg.SIGN_EQUAL, 0, -1, 0)
revert = gg.getResults(100000, nil, nil, nil, nil, nil, nil, nil, nil)
gg.editAll(":", gg.TYPE_BYTE)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC | gg.REGION_ANONYMOUS | gg.REGION_CODE_APP)
gg.searchNumber(":tss_sdk_gen_session_data", gg.TYPE_BYTE, false, gg.SIGN_EQUAL, 0, -1, 0)
revert = gg.getResults(100000, nil, nil, nil, nil, nil, nil, nil, nil)
gg.editAll(":", gg.TYPE_BYTE)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC | gg.REGION_ANONYMOUS | gg.REGION_CODE_APP)
gg.searchNumber(":tss_sdk_regist_tss_info_receiver", gg.TYPE_BYTE, false, gg.SIGN_EQUAL, 0, -1, 0)
revert = gg.getResults(100000, nil, nil, nil, nil, nil, nil, nil, nil)
gg.editAll(":", gg.TYPE_BYTE)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC | gg.REGION_ANONYMOUS | gg.REGION_CODE_APP)
gg.searchNumber(":tss_sdk_wait_verify", gg.TYPE_BYTE, false, gg.SIGN_EQUAL, 0, -1, 0)
revert = gg.getResults(100000, nil, nil, nil, nil, nil, nil, nil, nil)
gg.editAll(":", gg.TYPE_BYTE)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC | gg.REGION_ANONYMOUS | gg.REGION_CODE_APP)
gg.searchNumber(":tss_log_str", gg.TYPE_BYTE, false, gg.SIGN_EQUAL, 0, -1, 0)
revert = gg.getResults(100000, nil, nil, nil, nil, nil, nil, nil, nil)
gg.editAll(":", gg.TYPE_BYTE)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC | gg.REGION_ANONYMOUS | gg.REGION_CODE_APP)
gg.searchNumber(":tss_enable", gg.TYPE_BYTE, false, gg.SIGN_EQUAL, 0, -1, 0)
revert = gg.getResults(100000, nil, nil, nil, nil, nil, nil, nil, nil)
gg.editAll(":", gg.TYPE_BYTE)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC | gg.REGION_ANONYMOUS | gg.REGION_CODE_APP)
gg.searchNumber(":tp2_free_anti_data", gg.TYPE_BYTE, false, gg.SIGN_EQUAL, 0, -1, 0)
revert = gg.getResults(100000, nil, nil, nil, nil, nil, nil, nil, nil)
gg.editAll(":", gg.TYPE_BYTE)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC | gg.REGION_ANONYMOUS | gg.REGION_CODE_APP)
gg.searchNumber(":GetTssExportFunc2", gg.TYPE_BYTE, false, gg.SIGN_EQUAL, 0, -1, 0)
revert = gg.getResults(100000, nil, nil, nil, nil, nil, nil, nil, nil)
gg.editAll(":", gg.TYPE_BYTE)
gg.clearResults()
gg.setRanges(gg.REGION_C_ALLOC | gg.REGION_ANONYMOUS | gg.REGION_CODE_APP)
gg.searchNumber(":TssSDKOnRecvData", gg.TYPE_BYTE, false, gg.SIGN_EQUAL, 0, -1, 0)
revert = gg.getResults(100000, nil, nil, nil, nil, nil, nil, nil, nil)
gg.editAll(":", gg.TYPE_BYTE)
gg.clearResults()
end
function SAIR()
 print("@Zark Mod")
 os.exit()
  end
  function HOME()
    lw=1
    ATT()
  end
  sj = os.date("12/04/2022")
  
  while(true)do
    if gg.isVisible(true) then
      XGCK=1
      gg.setVisible(false)
    end
    gg.clearResults()
    if XGCK==1 then
      ATT()
    end
   end
