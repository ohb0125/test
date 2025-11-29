// (scanf 보안 경고 무시)
#define _CRT_SECURE_NO_WARNINGS 
#include <stdio.h>

// 1. 점수 구조체 선언 
// 'struct Score'라는 이름을 지어줍니다.
struct Score {
    int kor;
    int eng;
    int math;
};

// 2. 학생 구조체 선언
// 'struct Student' 안에 'struct Score'를 포함시킵니다.
struct Student {
    char name[20];
    int id;
    struct Score grade; // [중요] 자료형을 'struct Score'라고 다 적어야 합니다.
};

// [함수] 수학 점수 정정 (Call by Address)
// 매개변수에서도 'struct Student*'라고 풀네임을 써야 합니다.
void updateMathScore(struct Student* p, int newScore) {
    p->grade.math = newScore;
    printf("\n>> 수학 점수를 %d점으로 수정했습니다.\n", newScore);
}

// [함수] 성적표 출력 (Call by Value)
void printReport(struct Student s) {
    int total = s.grade.kor + s.grade.eng + s.grade.math;
    double avg = total / 3.0;

    printf("\n--- [%s] 학생 성적표 ---\n", s.name);
    printf("학번: %d\n", s.id);
    printf("국어: %d, 영어: %d, 수학: %d\n", s.grade.kor, s.grade.eng, s.grade.math);
    printf("총점: %d점 (평균: %.1f점)\n", total, avg);
    printf("------------------------\n");
}

int main() {
    // [중요] 변수 선언 시 앞에 'struct'를 꼭 붙여야 합니다.
    struct Student s1;
    int new_math;

    printf("=== 학생 정보 입력 ===\n");

    // 1. 이름 입력
    printf("이름: ");
    scanf("%s", s1.name); // 배열은 & 생략

    // 2. 학번 입력
    printf("학번: ");
    scanf("%d", &s1.id);  // 변수는 & 필수

    // 3. 점수 입력 (중첩된 구조체 접근)
    // s1.grade.kor 순으로 점(.)을 찍고 들어갑니다.
    printf("국어 영어 수학 점수 (공백으로 구분): ");
    scanf("%d %d %d", &s1.grade.kor, &s1.grade.eng, &s1.grade.math);

    // 입력 확인
    printReport(s1);

    // --- 추가 기능: 점수 수정 ---
    printf("\n수정할 수학 점수를 입력하세요: ");
    scanf("%d", &new_math);

    // 함수 호출 (주소 전달 &s1)
    updateMathScore(&s1, new_math);

    // 수정 결과 확인
    printReport(s1);

    return 0;
}
