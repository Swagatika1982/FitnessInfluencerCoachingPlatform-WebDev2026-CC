# FitnessInfluencerCoachingPlatform-WebDev2026-CC
ER diagram design for an online fitness coaching platform with trainers, clients, subscriptions, sessions, check-ins, progress tracking, and payments.

 https://app.eraser.io/workspace/KUCJo8e0p5x2XBhLqiG9?origin=share

 # Online Fitness Coaching Platform - ER Diagram

This project contains the ER diagram design for an **online fitness coaching platform**.

The platform is designed for a business where one or more **trainers / fitness influencers** manage multiple **clients** and provide structured online coaching support.

## Project Overview

The system supports features such as:

- trainer and client management
- coaching plans / programs
- client subscriptions
- payment tracking
- consultations and sessions
- weekly check-ins
- progress tracking
- trainer notes and feedback

This is not a gym management system.  
It is an online coaching ecosystem where trainers provide fitness support digitally.

## Business Scenario

A fitness influencer starts by coaching clients through Instagram DMs and video calls. As the business grows, they need a platform to manage:

- onboarding clients
- selling coaching plans
- scheduling consultations
- managing subscriptions
- tracking progress
- maintaining regular check-ins

Some users may join only for a consultation, while others may subscribe to long-term coaching programs.

## Main Entities Included

The ER diagram includes the following core entities:

- User
- TrainerProfile
- ClientProfile
- ProgramPlan
- ClientSubscription
- Payment
- Session
- CheckIn
- ProgressEntry
- TrainerNote

## Key Design Decisions

- A common **User entity is used for shared account details.
- TrainerProfile and **ClientProfile are separated to avoid mixing role-specific data.
- ProgramPlan stores the coaching plans offered by trainers.
- ClientSubscription tracks which client purchased which plan and for what duration.
- Session is modeled separately from CheckIn because consultations and weekly reports are different.
- ProgressEntry stores measurable fitness data like weight and body measurements.
- TrainerNote stores trainer feedback separately for better normalization.
- Payment is linked to subscriptions to support one-time or repeated payments. 

## Files in this Repository

This repository include:

- ER diagram image   
- README documentation

## Learning Goal

This project was created to practice:

- business understanding
- entity identification
- PK/FK mapping

## Conclusion

This ER diagram presents a simple and practical database structure for a real-world online fitness coaching platform. The model is designed to be  beginner-friendly, and easy to extend in the future.
