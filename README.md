# chatbot-function
helpful codes to make a chatbot
> 2018년 11월 이후로 카카오톡 챗봇 api가 막힘에 따라 더이상 사용 불가능합니다.
> 페이스북 메신저 챗봇은 그대로 사용 가능.

## chat.php
>
> 카카오톡 챗봇 응답을 편하게 할수있도록 제작한 함수입니다.
> 원형은 kakao ($text , $photo , $url , $input)
>

### text
>
> 카카오톡 챗봇 대화창에 나올 글씨입니다  
> 문자열 하나를 받아와서 그대로 출력합니다.  
> 꼭 필요한 부분이므로, 생략 불가능합니다.  
>

### photo
>
> 챗봇 메시지 아래에 나올 사진입니다.  
> 0을 적거나 Null을 보내주면 자동으로 생략이 가능합니다.  
> 반드시 배열값을 보내주어야 하며, array ($url , $width , $height)의 형태를 가집니다  
>> 첫번째 배열값에는 사진의 링크를 적어주어야 하며, 문자열을 받을수 있습니다.  
>> 두번째 배열값에는 사진의 가로길이를 적어주어야 하며, 숫자만 받을수 있습니다.  
>> 세번째 배열값에는 사진의 세로길이를 적어주어야 하며, 숫자만 받을수 있습니다.  
>

### url
>
> 챗봇 메시지 아래에 나올 주소입니다.  
> 0을 적거나 Null을 보내주면 자동으로 생략이 가능합니다.  
> 반드시 배열값을 보내주어야 하며, array ($label , $url)의 형태를 가집니다  
>> 첫번째 배열값에는 링크 버튼에 보여질 글씨를 입력해야하며, 문자열만 받을수 있습니다.  
>> 두번째 배열값에는 링크를 입력해야하며, 문자열만 받을수 있습니다. 
> 

### input(keyboard)
>
> 챗봇의 하단에 나오는 입력 버튼입니다.  
> 0 또는 Null을 보내주면 키보드가 활성화되며,  
> 배열값을 보내주면 버튼이 활성화됩니다.  
>
