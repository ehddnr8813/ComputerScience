Eclipse DTD 파일 등록

- 이클립스에서 XML파일(맵핑이나 설정파일 등등)을 편집할 경우 자동완성 기능이 지원된다.

- 개발 현장에 따라서 보한 혹은 인프라 문제로 인터넷을 사용할 수 없을 때 자동완성이 잘 동작하지 않을 수 있다.

- 이런 자동완성 기능은 XML 과 같은 마크업 문서의 형식을 정의하는 DTD(Document Type Definition)를 참조하여 제공되고 있으며 해당 파일의 상단에 DOCTPYE으로 선언된다.

- configuration에는 confing 을 mapper파일에는 mapper를

  <!DOCTYPE configuration
  	PUBLIC "-//mybatis.org/DTD Config 3.0//EN"
  	"http://mybatis.org/dtd/mybatis-3-config.dtd">

<?xml version="1.0" encoding="UTF-8"?>

<!DOCTYPE configuration
	PUBLIC "-//mybatis.org/DTD Config 3.0//EN"
	"http://mybatis.org/dtd/mybatis-3-mapper.dtd">