% Author Name: Joshua Oliveira
% Email: olivei64@rowan.edu
% Course: MATLAB Programming - Fall 2024
% Assignment: Midterm
% Task: Ace the Midterm
% Date: November 13, 2024
classdef Student
    properties
        ID
        Name
        Age
        GPA
        Major
    end
    
    methods
        % Creating student objects
        function obj = Student(student_id, name, age, gpa, major)
            if nargin > 0  % Check arguments validity
                obj.ID = student_id;
                obj.Name = name;
                obj.Age = age;
                obj.GPA = gpa;
                obj.Major = major;
            end
        end
        
        % Display student info
        function displayInfo(obj)
            fprintf('ID: %d, Name: %s, Age: %d, GPA: %.2f, Major: %s\n', ...
                obj.ID, obj.Name, obj.Age, obj.GPA, obj.Major);
        end
        
        % Update GPA
        function obj = updateGPA(obj, new_gpa)
            if new_gpa >= 0 && new_gpa <= 4
                obj.GPA = new_gpa;
            else
                error('GPA must be between 0 and 4.');
            end
        end
    end
end
