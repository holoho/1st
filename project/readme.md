
# Characteristics of Korean Beef Appearance Examination


columns = 52

arn, diff, LOC, BCS, Mperson, Mym, iMage, Mage, Sym, iSage, Sage, T1, T2, T3, T4, T5, T6,T7, T8, T9, T10, T11, T12, T13,T14, T15, T16, T17, T18, T19,G1,G2,G3,G4,G5,G6, FS, BH,BL,BD,RL,HL,cw,ema,bf,ms,tprice,p_cw, p_ema, p_bf, p_ms, p_tprice

arn = 개체 번호

diff = iSage-iMage = 도축 때 나이 – 심사 때 나이

LOC = 심사한 장소(농장)

Mperson = 심사자

Mym = 심사년월   		Sym = 도축 년월

iMage = 심사 때 개체 나이(월령)	iSage = 도축 때 개체 나이(월령)

Mage = 심사월령/30		Sage = 도축월령/30

T1~T19 = 심사형질

G1~G6 = 등급형질

FS = final score

BH = 체고

BL = 체장

BD = 흉심

RL = 고장

HL = 오각장

cw= 도체중

ema = 등심단면적

bf = 등지방 두께

ms = 근내지방도

tprice = 육량가격

p_cw, p_ema, p_bf, p_ms, p_tprice = 각 형질별 예측값

target values = CW, EMA, BF, MS

used multiclass classification and multiclass-multioutput classficiation for multiple features and multiple target values

data shape -> 970,914 * 52
