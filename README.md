=IFERROR(IF(VLOOKUP(A2,Sheet1!A:D, 4,false)=B2,"❌ Duplicate", "⚠️ Duplicate, description not same"),"✅ New item")
