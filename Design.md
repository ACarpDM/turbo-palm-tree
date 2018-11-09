#Assignment Manager

James Wang, Ian Hirsch, Xiao Shan, Drew Bradley

An non-obtrussive assignment manager which students to easily track their assignments. Optionally, they can get an estimate on how long it will take to complete this assignment based on past assigments.

Primary stakeholders: students. They will directly benefit from getting their homework done.
Secondary stakeholder: teachers. They will indirectly benefit from homework being done as it will lead to higher grades and that may or may not influence salary
Secondary stakeholder: parents. They will benefit from their children being successful and thus paying for retirement.

The primary output will be a non-obtrussive list of assignments, including due date. Optionally, there may be additional data such as estimate completion time or suggested start time, if the user chooses to enter such data. Example: see diagrams

For input, the only required data are assignment name and due date. Optionally, the user may input start/end dates, assignment details, associated class, and assignement type/category.

Name: P4       Due date: 11/19        Started Working: 11/18       Submitted: 11/19       Type: Program         Class: CS400       

See diagrams for actual appearance in GUI



#Class Summary:

##GUI - Manages all the GUI components, communicates w/ Assignement List
-createAssignment()
-loadData()
-updateAssignment()
-save()
-load()

##AssignmentList - Manages all the data
-createAssignment(String[] data)
-updateAssignment(int id, String[] data)
-getAssignements(filter=None)

##Assignment - Stores data for a single assignment
-getData()
-setData()


##Save - saves data
-save(AssignmentList)

##Load - loads data
-load(String fileLocation)
