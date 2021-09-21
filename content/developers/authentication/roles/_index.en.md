---
title: "Roles"
weight: 2
draft: false
# search related keywords
keywords: ["authentication","users", "roles"]
---
{{< notice info >}}
  **This page is under construction** <br>
  We're working on it!
{{</ notice >}}


Following table shows current system roles in the TeSLA system:

Role | Area | Description | Assigned by
--- | ----- | ---- | ----------
GLOBAL_ADMIN | Global | Manages and monitors the entire system. <br> Manages institutions. <br> Manages providers. <br> Manages instruments. <br> Required to access url:  api/v2/admin/** | GLOBAL_ADMIN: It can only be assigned by another user with this role. |
ADMIN | Institution | Manages institution settings. <br>Manages institution roles. <br>Required to access url:  api/v2/institution/<institucio>/** | It can be assigned by another ADMIN user, or by a GLOBAL_ADMIN.
SEND | Institution | Manages students with special needs properties. | ADMIN role from same institution.
DATA_MANAGEMENT | Institution | Manages update/delete data linked to GPRD ARCO permissions | ADMIN role from same institution.
IC_MANAGEMENT | Institution| Manages the informed consent of an institution | ADMIN role from same institution.
INSTRUCTOR | Institution | Manages the activities from own instituion | See information and results of students linked to their subjects| This role is not assigned, it is generated from a user's assignments
LEARNER | Institution | See his/her own information as student. | Make records on biometric instruments. | See results of the activities in which she/he has participated. | This role is not assigned, it is generated from a user's assignments
ACADEMIC_MANAGEMENT | Institution | See the results and statistics of a set of subjects. | ADMIN role from same institution.









******


Musce libero nunc, dignissim quis turpis quis, semper vehicula dolor. Suspendisse tincidunt consequat quam, ac posuere leo dapibus id. Cras fringilla convallis elit, at eleifend mi interam.

{{< notice note >}}
  This is a simple note.
{{</ notice >}}

{{< notice tip >}}
  This is a simple tip.
{{</ notice >}}

{{< notice info >}}
  This is a simple info.
{{</ notice >}}


{{< tabs >}}
  {{< tab "first" >}}
   This is first tab
  {{</ tab >}}

  {{< tab "second" >}}
  this is second tab
  {{</ tab >}}

  {{< tab "third" >}}
  this is third tab
  {{</ tab >}}
{{</ tabs >}}

Nulla non sollicitudin. Morbi sit amet laoreet ipsum, vel pretium mi. Morbi varius, tellus in accumsan blandit, elit ligula eleifend velit, luctus mattis ante nulla condimentum nulla. Etiam vestibulum risus vel arcu elementum eleifend. Cras at dolor eget urna varius faucibus tempus in elit.

### Image Example

Nunc porta malesuada porta. Etiam tristique vestibulum dolor at ultricies. Proin hendrerit sapien sed erat fermentum, at commodo velit consectetur.

![image example](img-1.jpg "image")

Etiam vestibulum risus vel arcu elementum eleifend. Cras at dolor eget urna varius faucibus tempus in elit. Cras a dui imperdiet, tempus metus quis, pharetra turpis. Phasellus at massa sit amet ante semper fermentum sed eget lectus. Quisque id dictum magna, et dapibus turpis.

### Example Of Code Block

In accumsan lacus ac neque maximus dictum. Phasellus eleifend leo id mattis bibendum. Curabitur et purus turpis. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia Curae;

```html
<head>
  <meta charset="utf-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="/assets/css/main.css">
  <link rel="shortcut icon" type="image/png" href="/assets/img/favicon.png" >
  <script src="/assets/js/main.js"></script>
</head>
```

### Text and Quote

Cras at dolor eget urna varius faucibus tempus in elit. Cras a dui imperdiet, tempus metus quis, pharetra turpis. Phasellus at massa sit amet ante semper fermentum sed eget lectus. Quisque id dictum magna turpis.

> Etiam vestibulum risus vel arcu elementum eleifend. Cras at dolor eget urna varius faucibus tempus in elit. Cras a dui imperdiet

Etiam vestibulum risus vel arcu elementum eleifend. Cras at dolor eget urna varius faucibus tempus in elit. Cras a dui imperdiet, tempus metus quis, pharetra turpis. Phasellus at massa sit amet ante semper fermentum sed eget lectus. Quisque id dictum magna, et dapibus turpis.Etiam vestibulum risus vel arcu elementum eleifend. Cras at dolor eget urna varius faucibus tempus in elit. Cras a dui imperdiet, tempus metus quis, pharetra turpis. Phasellus at massa sit amet ante semper fermentum sed eget lectus. Quisque id dictum magna, et dapibus turpis.