## PW Live Class FE Repository
## Table of Contents
1. [Project Overview](#project-overview)
2. [Tech Stack](#tech-stack)
3. [Prerequisites](#prerequisites)
4. [Getting Started](#getting-started)
5. [Usage](#usage)

## Project Overview <a name="project-overview"></a>
- **Purpose**:
    - Prupose
- **Features**:
    - Features

## Tech Stack <a name="tech-stack"></a>
List of all technical stack utilized in the project:
- NextJS
- Typescript
- Redux
- Tailwind CSS
- React Query

## Prerequisites <a name="prerequisites"></a>
Before you begin, ensure you have the following dependencies installed:
- Node.js V16

## Getting Started <a name="getting-started"></a>
Follow these steps to get the project up and running:

### Setup Instructions <a name="setup-instruction"></a>
1. **Clone the Repository:**
    - Open your terminal and execute the following commands:
    ```bash
    git clone https://gitlab.com/penpencil-services/uxcc/pw-live-class-fe.git
    ```
 
    - This will clone the project from the specified branch (`initial-commit`) of the GitLab repository. 

    ```bash
    cd pw-live-class-fe
    ```
2. **Install npm:**
    - To install npm, run the following command
    ```bash
    npm install --legacy-peer-deps
    ```
3. **Start Development Servers:**
    - Prerequisites to run locally:- 
      1. First, you have to login on <a href="https://staging.physicswallah.live/study/auth?url=" target="_blank">Stage Auth Server</a>. The OTP will be `123456` on stage auth server.
      2. You have to copy the value of these keys `user` as `Object`, `token/TOKEN` as `String`,randomId from local storage.
      3. There is a Cred.json file which contains these keys `_User`, `_Token` and `_RandomI`d. and paste values. `_User` and `Token` keys are mandtory to update.
    
    - Execute the following command:
    ```bash
    npm run dev 
    ```
    
    - PORT `3000`
    - URL: `localhost:3000/`
    - Sample url for live-class[Local] - `http://localhost:3000/classroom/pw-live-class/6671330ded18bda94d0896ea`
    - Sample url for live-class[Stage]- `https://staging.physicswallah.live/classroom/pw-live-class/65d49f551b64230018f40349`
    - Sample url for live-class[Prerod]- `https://demo.pw.live/classroom/pw-live-class/6606b554b86e830018b6a665`
    - Sample url for live-class[Prod] -`https://pw.live/classroom/pw-live-class/65d49f551b64230018f40349`
    - Sample url for teacher[Stage]- `https://teacher-v2-stage.physicswallah.live/classroom/pw-live-class-teacher/66704238dd285463fc21ec8a`
    - Sample url for teacher[Prod] `https://teacher.physicswallah.live/classroom/pw-live-class-teacher/66070018186b4b00185640f9`
      

## Usage <a name="usage"></a>
- This project does not require explicit usage instructions
