# 【第27回_Beginner限定コンペ】債務不履行リスクの低減
https://signate.jp/competitions/743


## コンペ概要
### 期間
2022/10/01 ~ 2022/10/31

### 内容
借入金額や金利，借入目的など9の変数から，顧客が債務不履行に陥るかどうかを予測するコンペティション．  
データ件数は242,150件．  
評価方法はF1 Score.  

## 結果
順位：8位/161人中  
最終スコア：F1 Score = 0.3919794  
１位のスコア：F1 Score = 0.3946346  


## コンペメモ：
### 説明変数：
id:                  顧客id  
loan_amnt:           借入金額  
term:                借入期間  
interest_rate:       金利  
grade:               顧客等級  
employment_length:   勤続年数  
purpose:             借入目的  
credit_score:        クレジットスコア  
application_type:　　 借入申込種別(個人 or 連名)  
loan_status(目的変数): 債務不履行に陥ったかどうか  

### 感想：
初のコンペ参加．交互作用項や，集約統計量，ターゲットエンコーディングなど，特徴量エンジニアリングの経験を積んだ．