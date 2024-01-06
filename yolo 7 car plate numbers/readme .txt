in the loss.py file int the yolo7 /utils  at the line of 759 write this code to resolve the error: 


if fg_mask_inboxes.device != from_which_layer.device:
    from_which_layer = from_which_layer.to(fg_mask_inboxes.device)