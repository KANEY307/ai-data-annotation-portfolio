
# Project 001: Video Annotation & Object Tracking

## Project Overview

This project demonstrates video annotation techniques used in computer vision and machine learning dataset preparation.

The objective is to identify objects, assign consistent labels, track objects across frames, and record timestamps.

**Project type:** Demonstration project  
**Annotation method:** Bounding boxes and object tracking  
**Dataset:** Illustrative sample scenario  
**Resolution:** 1920 × 1080

## Annotation Objectives

1. Identify objects in video frames.
2. Draw accurate bounding boxes.
3. Assign unique tracking IDs.
4. Record timestamps.
5. Maintain object identity across frames.
6. Perform annotation quality checks.

## Sample Annotation Scenario

A pedestrian is walking along a street while a car moves along the road.

| Frame | Timestamp | Object | Track ID | Action |
|---|---|---|---|---|
| 001 | 00:00:01.000 | Person | 001 | Walking |
| 001 | 00:00:01.000 | Car | 002 | Moving |
| 002 | 00:00:02.000 | Person | 001 | Walking |
| 002 | 00:00:02.000 | Car | 002 | Moving |
| 003 | 00:00:03.000 | Person | 001 | Walking |
| 003 | 00:00:03.000 | Car | 002 | Moving |

## Bounding Box Demonstration

Image resolution: 1920 × 1080 pixels.

Example coordinates:

| Object | X | Y | Width | Height |
|---|---:|---:|---:|---:|
| Person | 420 | 180 | 260 | 700 |
| Car | 1000 | 450 | 500 | 300 |

Coordinates use the top-left corner as the origin.

## Object Tracking

The same tracking ID is maintained for an object across consecutive frames.

- Person: Track ID 001
- Car: Track ID 002

Tracking IDs should only change when a new object appears or an existing identity cannot reliably be maintained.

## Quality Assurance

- Check bounding box placement.
- Verify object labels.
- Check tracking ID consistency.
- Review timestamps.
- Identify missing or duplicate annotations.
- Follow the annotation guidelines.

## Tools

- CVAT
- Label Studio
- Supervisely
- Roboflow

## Skills Demonstrated

Video annotation, object detection, bounding boxes, object tracking, timestamp labeling, action recognition, and annotation quality assurance.

