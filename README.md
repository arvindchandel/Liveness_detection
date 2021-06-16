# Liveness_detection

1. To run the blink detection app use the command below

   python3 blink_detection.py --shape-predictor shape_predictor_68_face_landmarks.dat
   
   Note: Download the 'shape_predictor_68_face_landmarks.dat' file from link below and keep it in blink_detection directory.
   
   https://euclidinnovationsinc.sharepoint.com/sites/camldev/Shared%20Documents/General/Shared%20Files/shape_predictor_68_face_landmarks.dat
   
 
 2. To run the gaze_tracking based liveness detection app, go inside gaze_tracking directory and run the command below:
 
    python3 example.py
    
    Note: You need to use 'shape_predictor_68_face_landmarks.dat' file here as well, and keep it in 'gaze_tracking/gaze_tracking/trained_models' directory.
