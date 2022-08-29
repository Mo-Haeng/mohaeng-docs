

# 모행 - 모임 도움 서비스

</br>

동아리나 스터디 등을 모집 & 가입하고, 그룹만의 게시판과 단채&개인 채팅 기능을 통해 실시간으로 소통하며,

특정 모임에 가입한 인원들의 명단 관리와, 가입비 혹은 특정 활동에 대한 참여비 결제와, 지불 여부 확인과 출석체크 등의 모임에 대한 종합적인 기능을 제공하는 것을 목표로 합니다.

또한 명단과 참여 설문조사 등을 엑셀 파일로 변환하여 문서 관리도 쉽고 간편하게 이용할 수 있습니다. 



</br>
</br>
</br>

# Services

## mohang-discovery
```
서비스들을 등록
```



</br>
</br>

## mohang-gateway
```
JWT를 가지고 인증 수행, 인증정보를 각각의 서비스들의 요청으로 라우팅하면서 전달함
```
	
</br>
</br>

## mohang-meeting 
```
mohang-meeting-core 
- 모임 생성, 수정, 삭제, 모집, 인원 추가&감소(가입 수락 시 인원 추가), 더치패이 등 

mohang-meeting-query 
- 모임 목록 조회
		
mohang-meeting-document
- 모임에 가입한 인원들 명단 문서화

mohang-meeting-batch

mohang-meeting-admin

mohang-meeting-participation
- 가입신청, 탈퇴, 가입 수락, 가입 거절,
```

</br>
</br>



## mohang-activity 
```
mohang-activity-core
- 활동 모집, 활동 명단관리(참가자, 비용지불 여부 등)

mohang-activity-query
- 활동 목록 조회
		
mohang-activity-document
- 활동 명단 문서화

mohang-activity-participation
- 활동 신청, 활동 수락&거절, 활동 신청 취소 등
```

</br>
</br>

## mohang-payment
```
- 모임 가입비 혹은 활동비 결제 서비스(진짜 돈을 가지고 결제하는 서비스)
```	
</br>
</br>

## mohang-alram
```
- 알람 기능 담당 (실제 알림을 보내는 서비스)
```	
</br>
</br>

## mohang-board
```
- 모임별 게시판 기능(공지, 잡설 등), 전체 사용자 대상으로 하는 게시판 기능도 제공
```	
</br>
</br>

## mohang-chatting
```
- 모임별 채팅 & 개인별 채팅 기능 제공
```
	
</br>
</br>

## mohang-member
```
mohang-member-core
- 회원 가입, 회원 탈퇴, 회원정보 수정 등

mohang-member-auth
- 로그인, 로그아웃등의 기능 제공

mohang-member-batch

mohang-member-admin

mohang-member-query
```
</br></br></br>



