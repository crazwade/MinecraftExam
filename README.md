# MinecraftExam

首頁
index.html?name=[學生姓名] => result.html?name=[學生姓名]&date=[日期]

資料庫

root

    Stu
    
        學生姓名
        
            日期
            
                <!-- 學生答題成績圖 -->
                png:?.png
                
                <!-- 成績 -->
                score:?
                
    data
    
        日期
        
            <!-- 平均成績圖 -->
            avg:avg.png 
            
            <!-- 詳細數據分析圖 -->
            detail:detail.png
            
{
  "Stu" : {
    "Jacky" : {
      "1111" : {
        "png" : "10.png",
        "score" : "80"
      },
      "2222" : {
        "png" : "10.png",
        "score" : "80"
      }
    }
  },
  "data" : {
    "20210321" : {
      "avg" : "avg.png",
      "detail" : "detail.png"
    }
  }
}

