<!-- To insert document for Users collection -->

db.Users.insertMany([
  { "user_id": 1, "name": "Praveen", "gender": "Male", "work_experience": 2, "placement_appeared": "yes", "placement_company": "Zoho" },
  { "user_id": 2, "name": "Angel", "gender": "Female", "work_experience": 1, "placement_appeared": "no", "placement_company": null },
  { "user_id": 3, "name": "Rahul", "gender": "Male", "work_experience": 3, "placement_appeared": "yes", "placement_company": "Wipro" },
  { "user_id": 4, "name": "Sneha", "gender": "Female", "work_experience": 5, "placement_appeared": "yes", "placement_company": "Accenture" },
  { "user_id": 5, "name": "Vikram", "gender": "Male", "work_experience": 2, "placement_appeared": "no", "placement_company": null },
  { "user_id": 6, "name": "Ananya", "gender": "Female", "work_experience": 4, "placement_appeared": "yes", "placement_company": "Prodapt" },
  { "user_id": 7, "name": "Amit", "gender": "Male", "work_experience": 6, "placement_appeared": "no", "placement_company": null },
  { "user_id": 8, "name": "Neha", "gender": "Female", "work_experience": 1, "placement_appeared": "yes", "placement_company": "TCS" },
  { "user_id": 9, "name": "Rajesh", "gender": "Male", "work_experience": 7, "placement_appeared": "no", "placement_company": null },
  { "user_id": 10, "name": "Pooja", "gender": "Female", "work_experience": 3, "placement_appeared": "yes", "placement_company": "Verizon" },
  { "user_id": 11, "name": "Rohan", "gender": "Male", "work_experience": 4, "placement_appeared": "yes", "placement_company": "HCL" },
  { "user_id": 12, "name": "Divya", "gender": "Female", "work_experience": 5, "placement_appeared": "no", "placement_company": null }
]);


<!-- To insert document for Codekata collection -->

db.Codekata.insertMany([
  { "No_of_problems_solved": 10, "user_id": 1 },
  { "No_of_problems_solved": 15, "user_id": 2 },
  { "No_of_problems_solved": 7,  "user_id": 3 },
  { "No_of_problems_solved": 20, "user_id": 4 },
  { "No_of_problems_solved": 9,  "user_id": 5 },
  { "No_of_problems_solved": 12, "user_id": 6 },
  { "No_of_problems_solved": 25, "user_id": 7 },
  { "No_of_problems_solved": 30, "user_id": 8 },
  { "No_of_problems_solved": 5,  "user_id": 9 },
  { "No_of_problems_solved": 14, "user_id": 10 },
  { "No_of_problems_solved": 18, "user_id": 11 },
  { "No_of_problems_solved": 22, "user_id": 12 }
]);


<!-- To insert document for Attendance collection(Collecting the absentees on the date of october) -->

db.Attendance.insertMany([
  { "user_id": 1, "date": new Date("2024-10-15"), "status": "Absent" },
  { "user_id": 2, "date": new Date("2024-10-16"), "status": "Absent" },
  { "user_id": 2, "date": new Date("2024-10-17"), "status": "Absent" },
  { "user_id": 1, "date": new Date("2024-10-18"), "status": "Absent" },
  { "user_id": 4, "date": new Date("2024-10-19"), "status": "Absent" },
  { "user_id": 4, "date": new Date("2024-10-20"), "status": "Absent" },
  { "user_id": 1, "date": new Date("2024-10-21"), "status": "Absent" },
  { "user_id": 3, "date": new Date("2024-10-22"), "status": "Absent" },
  { "user_id": 9, "date": new Date("2024-10-23"), "status": "Absent" },
  { "user_id": 10, "date": new Date("2024-10-24"), "status": "Absent" },
  { "user_id": 10, "date": new Date("2024-10-25"), "status": "Absent" },
  { "user_id": 3, "date": new Date("2024-10-26"), "status": "Absent" },
  { "user_id": 4, "date": new Date("2024-10-27"), "status": "Absent" },
  { "user_id": 1, "date": new Date("2024-10-28"), "status": "Absent" },
  { "user_id": 1, "date": new Date("2024-10-29"), "status": "Absent" },
  { "user_id": 3, "date": new Date("2024-10-30"), "status": "Absent" },
  { "user_id": 9, "date": new Date("2024-10-31"), "status": "Absent" }
]);


<!-- To insert document for topic month-wise  -->

db.Topics.insertMany([
  { "topic": "html", "month": "August", "number_of_classes": 2 },
  { "topic": "css", "month": "September", "number_of_classes": 3 },
  { "topic": "tailwind", "month": "October", "number_of_classes": 3 },
  { "topic": "javascript", "month": "August", "number_of_classes": 3 },
  { "topic": "react", "month": "September", "number_of_classes": 2 },
  { "topic": "nodejs", "month": "October", "number_of_classes": 3 },
  { "topic": "html", "month": "September", "number_of_classes": 3 },
  { "topic": "css", "month": "October", "number_of_classes": 2 },
  { "topic": "javascript", "month": "August", "number_of_classes": 3 },
  { "topic": "tailwind", "month": "October", "number_of_classes": 2 },
  { "topic": "react", "month": "August", "number_of_classes": 2 },
  { "topic": "nodejs", "month": "September", "number_of_classes": 3 },
  { "topic": "React Hooks", "month": "August", "number_of_classes": 3 },
  { "topic": "MongoDB", "month": "September", "number_of_classes": 3 },
  { "topic": "JS Advanced", "month": "October", "number_of_classes": 3 },
  { "topic": "DOM Manipulation", "month": "August", "number_of_classes": 2 },
  { "topic": "React Hooks", "month": "September", "number_of_classes": 3 },
  { "topic": "MongoDB", "month": "October", "number_of_classes": 2 },
  { "topic": "JS Advanced", "month": "August", "number_of_classes": 3 },
  { "topic": "DOM Manipulation", "month": "September", "number_of_classes": 2 }
]);


<!-- To insert task month-wise and submition record -->

db.Tasks.insertMany([
  { "user_id": 1, "task": { "task": "HTML,CSS, Tailwind task" }, "month": "August", "status": "Submitted" },
  { "user_id": 2, "task": { "task": "HTML,CSS,Tailwind task" }, "month": "August", "status": "Not Submitted" },
  { "user_id": 3, "task": { "task": "HTML,CSS,Tailwind task" }, "month": "August", "status": "Submitted" },
  { "user_id": 4, "task": { "task": "HTML,CSS,Tailwind task" }, "month": "August", "status": "Not Submitted" },
  { "user_id": 5, "task": { "task": "HTML,CSS,Tailwind task" }, "month": "August", "status": "Not Submitted" },
  { "user_id": 6, "task": { "task": "HTML,CSS,Tailwind task" }, "month": "August", "status": "Submitted" },
  { "user_id": 7, "task": { "task": "HTML,CSS,Tailwind task" }, "month": "August", "status": "Not Submitted" },
  { "user_id": 8, "task": { "task": "HTML,CSS,Tailwind task" }, "month": "August", "status": "Submitted" },
  { "user_id": 9, "task": { "task": "HTML,CSS,Tailwind task" }, "month": "August", "status": "Submitted" },
  { "user_id": 10, "task": { "task": "HTML,CSS,Tailwind task" }, "month": "August", "status": "Not Submitted" },
  { "user_id": 11, "task": { "task": "HTML,CSS,Tailwind task" }, "month": "August", "status": "Submitted" },
  { "user_id": 12, "task": { "task": "HTML,CSS,Tailwind task" }, "month": "August", "status": "Not Submitted" },

  { "user_id": 1, "task": { "task": "React" }, "month": "September", "status": "Not Submitted" },
  { "user_id": 2, "task": { "task": "React" }, "month": "September", "status": "Submitted" },
  { "user_id": 3, "task": { "task": "React" }, "month": "September", "status": "Not Submitted" },
  { "user_id": 4, "task": { "task": "React" }, "month": "September", "status": "Submitted" },
  { "user_id": 5, "task": { "task": "React" }, "month": "September", "status": "Submitted" },
  { "user_id": 6, "task": { "task": "React" }, "month": "September", "status": "Not Submitted" },
  { "user_id": 7, "task": { "task": "React" }, "month": "September", "status": "Submitted" },
  { "user_id": 8, "task": { "task": "React" }, "month": "September", "status": "Not Submitted" },
  { "user_id": 9, "task": { "task": "React" }, "month": "September", "status": "Submitted" },
  { "user_id": 10, "task": { "task": "React" }, "month": "September", "status": "Not Submitted" },
  { "user_id": 11, "task": { "task": "React" }, "month": "September", "status": "Submitted" },
  { "user_id": 12, "task": { "task": "React" }, "month": "September", "status": "Not Submitted" },

  { "user_id": 1, "task": { "task": "React + Node" }, "month": "October", "status": "Not Submitted" },
  { "user_id": 2, "task": { "task": "React + Node" }, "month": "October", "status": "Not Submitted" },
  { "user_id": 3, "task": { "task": "React + Node" }, "month": "October", "status": "Not Submitted" },
  { "user_id": 4, "task": { "task": "React + Node" }, "month": "October", "status": "Not Submitted" },
  { "user_id": 5, "task": { "task": "React + Node" }, "month": "October", "status": "Submitted" },
  { "user_id": 6, "task": { "task": "React + Node" }, "month": "October", "status": "Submitted" },
  { "user_id": 7, "task": { "task": "React + Node" }, "month": "October", "status": "Submitted" },
  { "user_id": 8, "task": { "task": "React + Node" }, "month": "October", "status": "Submitted" },
  { "user_id": 9, "task": { "task": "React + Node" }, "month": "October", "status": "Not Submitted" },
  { "user_id": 10, "task": { "task": "React + Node" }, "month": "October", "status": "Not Submitted" },
  { "user_id": 11, "task": { "task": "React + Node" }, "month": "October", "status": "Not Submitted" },
  { "user_id": 12, "task": { "task": "React + Node" }, "month": "October", "status": "Submitted" }
]);


<!-- To insert document for conmpany drive collection -->

db.Company_drives.insertMany([
  { "company_name": "Zoho", "drive_date": new Date("2024-10-01") },
  { "company_name": "Accenture", "drive_date": new Date("2024-10-03") },
  { "company_name": "HCL", "drive_date": new Date("2024-10-15") },
  { "company_name": "Wipro", "drive_date": new Date("2024-10-16") },
  { "company_name": "Prodapt", "drive_date": new Date("2024-10-18") },
  { "company_name": "Verizon", "drive_date": new Date("2024-10-20") },
  { "company_name": "TCS", "drive_date": new Date("2024-10-28") }
]);

<!-- To insert document for Mentors collection -->

db.Mentors.insertMany([
  { "mentor_name": "Suresh", "no_of_mentees": 16},
  { "mentor_name": "Sathish", "no_of_mentees": 12},
  { "mentor_name": "Pughal",  "no_of_mentees": 10},
  { "mentor_name": "Deepika", "no_of_mentees": 21},
  { "mentor_name": "Banu",    "no_of_mentees": 25}
]);



<!-- To Find all the topics and tasks which are thought in the month of October -->

db.Tasks.aggregate([
  {
    $match: { "month": "October" }
  },
  {
    $facet: {
      tasks: [
        { $project: { "task": 1 } }
      ],
      topics: [
        { $lookup: {
            from: "Topics",
            localField: "month",
            foreignField: "month",
            as: "topics_info"
          }
        },
        { $unwind: "$topics_info" },
        { $project: { "topic": "$topics_info.topic" } }
      ]
    }
  }
])


<!-- To Find all the company drives which appeared between 15 oct-2020 and 31-oct-2020 -->

db.Company_drives.find({
  "drive_date": {
    $gte: new Date("2020-10-15"),
    $lte: new Date("2020-10-31")
  }
});


<!-- To Find all the company drives and students who are appeared for the placement -->

db.Users.aggregate([
  {
    $match: { "placement_appeared": "yes" }  
  },
  {
    $lookup: {
      from: "Company_drives",
      localField: "placement_company",
      foreignField: "company_name",
      as: "drive_info"
    }
  },
  {
    $unwind: "$drive_info"
  },
  {
    $project: {
      "name": 1,
      "placement_company": 1,
      "drive_info.company_name": 1,
      "drive_info.drive_date": 1
    }
  }
]);


<!-- To Find the number of problems solved by the user in codekata -->

db.Codekata.aggregate([
  {
    $group: {
      _id: "$user_id",
      total_problems_solved: { $sum: "$No_of_problems_solved" }
    }
  }
]);


<!-- To Find all the mentors with who has the mentee's count more than 15 -->

db.Mentors.aggregate([
  {
    $match: { "no_of_mentees": { $gt: 15 } } 
  },
  {
    $project: {  
      "mentor_name": 1,
      "no_of_mentees": 1
    }
  }
]);


<!-- To Find the number of users who are absent and task is not submitted  between 15 oct-2020 and 31-oct-2020 -->

db.Attendance.aggregate([
  {
    $match: {
      date: { $gte: new Date("2024-10-15"), $lte: new Date("2024-10-31") },
      status: "Absent"
    }
  },
  {
    $lookup: {
      from: "Tasks",                
      localField: "user_id",        
      foreignField: "user_id",      
      as: "task_info"               
    }
  },
  {
    $unwind: "$task_info"           
  },
  {
    $match: {
      "task_info.status": "Not Submitted",
      "task_info.month": "October"   
    }
  },
  {
    $project: {
      user_id: 1,
      date: 1,
      status: 1,
      "task_info.task": 1,
      "task_info.status": 1
    }
  }
]);
