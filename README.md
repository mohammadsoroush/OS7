                                                                                                                                                                          
                                                                                                                                                                     :سوال یک
                                                                                                                                                                     
                                                                                                                                                                     
                                            یک لینک در سیستم عامل یونیکس اشاره گر یا پوینتری به یک فایل یا دایرکتوری می باشد.ساختن لینک مثل زدن شورت کات در ویندوز است.
                                            
                                                                                                1-Symbolic links  2-Hard Links    : دو نوع لینک وجود دارد.
                 هارد لینک مثل کپی کردن فایل عمل میکند و اگر فایل اصلی پاک شود همچنان میتوان از طریق هارد لینک به فایل دسترسی داشت و نمیتوان دایرکتوری ها را لینک کرد.
                                   
                      لینک های سمبولیک مثل پوینتری به فایل مرجع است واگر فایل اصلی پاک شود دیگر نمیتوان از لینک سمبولیک استفاده کردو میتوان دایرکتوری ها را لینک کرد .
                                   
 symbolic link syntax:
 
 ln -s filename linkname
 
 Ex: ls -s videos videos_link
 
 
 hard link syntax:
 
 ls filename linkname
 
                                                                                                                                                                      سوال دوم:
                                                                                                                                                                      
                                
                           . استفاده میشود و همانطور که از اسمش پیداست لینک هایی میسازد که به مکان فایلمان وابسته باشد  -- relative or -r  این دستور همراه دستورات 
 
                                                                                                                                                                      سوال سوم:
                                                                                                                                                                      
                                                                                                      محل دایرکتوری که قرار است در آن لینک ساخته شود را مشخص میکند:-t
                                                                                                                           اسم هر فایل را قبل از لینک شدن چاپ میکند.:-v
                                                                                                                     با هر لینک مثل فایل اصلی و اورجینال رفتار میکند:-T
                                                                                                                                                                       
                                                                                                                                                                 :سوال چهارم
                                                                                                              این دستور برای تغییر دسترسی ها و مجوز ها استفاده میشود
                                                                                                                                                                          
                                                                                                
                                                                                                                                                                   
