#!/usr/bin/env python3
# coding: utf8
import Precaution
import Meirei
#import Izen
#import Renyou
#import Mizen

def prints(words):
    for word in words:
        if word is not None: print(word)
def get_mizens(row):
    return (mizen.get_not(row),
            mizen.get_not_old(row),
            mizen.get_conn(row),
            mizen.get_not_special(row),
            mizen.get_reru(row))
def get_renyous(row):
    return (renyo.get_howto(row),
            renyo.get_state(row),
            renyo.get_start(row),
            renyo.get_end(row),
            renyo.get_conn(row))
def get_izens(row):
    return (izen.get_ba(row),
            izen.get_domo(row),
            izen.get_tara(row),
            izen.get_reba(row),
            izen.get_ru(row),
            izen.get_reru(row),
            izen.get_min(row))
def get_meirei(row):
    return (meirei.get(row),)
#    return (meirei.get(row),
#            meirei.get_e(row),
#            meirei.get_ro(row),
#            meirei.get_yo(row),
#            meirei.get_i(row))

p = Precaution.Precaution()
#mizen = Mizen.Mizen()
#renyo = Renyou.Renyou()
#izen = Izen.Izen()
meirei = Meirei.Meirei()
words = ['走る','押す','愛する','見る','食べる','来る','悲しい','ござる']
for word in words:
    print('===== {} ====='.format(word))
    rows = p.get(word)
    for row in rows:
        prints(get_meirei(row))
"""
定まる,772,772,6852,動詞,自立,*,*,五段・ラ行,基本形,定まる,サダマル,サダマル

0: 語(word)
1,2,3:
4: 品詞(word_class)
5: 単語種別(word_type)
6,7:
8: 活用種別(conj_type) 
9: 活用形種別(conj)
10: 語の基本形(word_base)
11,12: 読み？発音？
"""
